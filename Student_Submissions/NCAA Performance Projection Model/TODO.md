#Project Roadmap: Athlete Performance Prediction

##Phase 1: Data Collection - College (Complete)
[x] Scrape college athlete race results (TFRRS)

##Phase 2: Data Collection - High School (Athletic.net)
###Current Focus: Optimization & Ingestion

####Live Site Web Hooks: 
[ ] Inspect network traffic to identify internal API endpoints/web hooks for live results to bypass full HTML parsing.

####Main Site Web Hooks: 
[ ] Identify hidden API calls for the main static site to improve scraping speed and reliability.

####Payload Analysis: 
[ ] Reverse engineer the JSON structure returned by the web hooks to map relevant fields (athlete ID, time, event).

####Script Implementation: 
[ ] Update scraper to utilize these endpoints instead of DOM traversal.

####Execution: 
[ ] Run batch scraping for target high school athletes.

####Normalization: 
[ ] Standardize event names and distances to match the college dataset.

##Phase 3: Training Data Acquisition
###Investigate data access methods (API limitations vs. public profile scraping).
[ ] Develop a strategy for matching athlete names/locations to profiles.

[ ] Collect publicly available training logs (mileage, workout types).

##Phase 4: Modeling & Prediction
[ ] Feature Engineering (Qualifying standards, seasonal performance).

[ ] Build prediction model for Indoor, Outdoor, and XC performance.