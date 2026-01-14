# Day 2

## Overview of class structure
 
 - Introduce common workflow
 - TODO template
 - Talk about local vs cloud
 - Folder structure, knowing your computer

---

# Keeping Your GitHub Fork Up to Date (Student Guide)

This guide explains how to get new course updates **from the original repository** into **your fork**.

---

## Key Idea (Memorize This)

- **Origin** = *your fork* (your personal copy)
- **Upstream** = *the original course repository*

> You **pull from upstream** to get new material  
> You **push to origin** to save your work

---

## One-Time Setup (Do This Once)

### GitHub Desktop 

1. Fork the course repository on GitHub
2. Clone **your fork** using GitHub Desktop
3. In GitHub Desktop:
   - Go to **Repository → Repository settings**
   - Confirm:
     - **Origin** = your fork
     - **Upstream** = course repository

If **Upstream** is missing:
- Click **Add remote**
- Name: `upstream`
- URL: *course repository URL*

---
## Weekly Routine (Do This Every Time Before You Work)

### GitHub Desktop
1. Click **Fetch origin**
2. Click **Fetch upstream**
3. Click **Update from upstream**
4. Start working

---

## What NOT to Do (Important)

- Do **not** pull from `origin` to get course updates
- Do **not** rebase
- Do **not** open pull requests *from upstream to your fork*

These cause most problems for beginners.

---

## If Something Goes Wrong

- Merge conflicts are **not errors**
- Git is telling you two changes disagree
- Ask for help — this is normal

Nothing is permanently broken.

---

## Quick Checklist

Before starting work:
- [ ] Pull from upstream
- [ ] Make changes
- [ ] Commit with a clear message
- [ ] Push to origin

---

## Reminder

GitHub remembers everything.  
You cannot permanently lose your work.
