# Attendance Tracker – Project Notes

## What this is
This project is to build a Google Meet attendance tracker.
We already have a partial working version (Attendance_Template_v3). Check it out for reference:

- Open the file
- Go to Extensions > Apps Script
- You’ll see the current logic (written in JavaScript, but pretty readable even if you know Python)

## Working with a team
We’ll use GitHub Projects to track and manage tasks.

All development will happen inside this repo, so it’s important to follow a few collaboration rules:

- Always create and work on your own branch
- This helps us review code before merging into main
- It also prevents us from accidentally overwriting each other’s work
- Place your working notebook(s) in: src/notebooks/
- When your branch is ready, open a pull request so others can review and discuss before merging

Following this workflow keeps the project organized, makes collaboration smoother, and protects everyone’s progress.  
[Git Refrence Sheet](https://docs.google.com/document/d/1sxmOdZr19dFgSs4NCmIMr-q76K5f_H2aBh16EIBzsMk/edit?usp=sharing)

## First steps / phase 1
Don’t worry about automation yet. Let’s focus on:

- Reading in the raw data (download via links in slack)
  - Make sure they are in the data folder and they are in the .gitignore 
- Writing a name validator
  - Some students have full names in the “first name” column etc.
- Adding a column with time in minutes format
- Building helper dataframes for mapping:
  - Class codes dataframe
  - Student dataframe
  - Mentor dataframe
  - Staff dataframe
- Adding logging:
  - Keeps track of which sheets we processed
  - Log errors and issues (like the existing tracker)
