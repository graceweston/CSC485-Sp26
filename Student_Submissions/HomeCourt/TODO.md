OVERALL TODO
1. Gather Data [X] 
3. Import Data [X]
   - NBA games data
   - Box scores
   Stadium locations
5. Clean/Filter Data [X]
   - keep only NBA games
   - remove preseason, duplicates, and missing outcomes
7. Standardize all variables [X]
8. Merge Datasets [X]
   - merge games plus attendance by gameID/date
   - merge stadium locations by home/away team
9. Create key variables [X]
   - ex. attendance, travel distance, back to back, rest days, season and date indicators, time zone
10. Exploratory Data Analysis [ ]
   - Home Win rate overall
   - Home Win rate by attendance
   - Home Win rate by travel
   - Compare rested vs back to back games
11. Statistical Modeling [ ]
    - Logistic Regression
    - Check coefficient signs and significants
12. Robustness Checks [ ]
    - Run models by season and exclude outlier seasons
13. Time Series Analysis [ ]
    - Plot home win percentage by season
    - Test whether home court advantage persists overtime
14. Geographic Analysis [ ]
    - Map stadium locations
    - Visualize win probability vs. travel distance
15. Interpret results [ ]
    - Identify strongest predictors
    - Connect findings back to research questions
16. Finalize Deliverables [ ]
    - Tables, figures, written conclusion
    - Delete gameID and league columns when we are completely done coding


FRIDAY 
- work on games.csv file
-    redirect the winner to a team name instead of an ID
-    get rid of all ID numbers
-    get rid of game type column and clean the columns
-    rename columns to match the stadiums file
COMPLETED ALL and started creating analysis equations and ideas

NEXT WEEK (2/2)
- combine stadiums and games data sets into 1 big data set [X]
- add columns
     - flag back to back games [X]
     - calculate distance traveled [X]
     - take into account time zones [X]
     - attendance brackets...?
     - clearer column showing if home team won or not (0/1 maybe) [X]
- can we break up the data by season so it's not so long....?
- fix LA Clippers and Lakers [X]

LAST WEEK (2/9)
- calculate home win rates listed above (by factor: overall, attendance, distance, time zone, back to back games) [X]
- visuals [X]

THIS WEEK (2/17)
- run statistical tests 
-    log reg?
-    random tree forest?
- find what are statistically significant factors
- stratify the graphs by the team to see if it just matters if they are good or bad
  (be weary about attendance)


Building/training models
- Regression?
     - Linear
     - Logistic
- Classification?
     - KNN
     - Random Forest

 **  Look at beta Binomial from last semester **
