# CMP 262 — Project 2, Part 1: Data Cleaning with pandas

**Due: Module 5**  
**Points: 20**

## Objective

Use Python and pandas to explore and clean the four Project 1 survey datasets. You will align the 2020 and 2021 surveys and create two analysis-ready CSV files:

- Computer Literacy survey (2020 and 2021 combined)
- Entry-Level Computing survey (2020 and 2021 combined)

## Getting Started

1. Select **Use this template → Create a new repository**.
2. Choose your personal GitHub account as the owner.
3. Name the repository:

   `LastName-FirstName-CMP262-Project02-Part01`

4. Set the repository to **Public** and select **Create repository**.
5. Clone **your new repository**, not the instructor repository.
6. Open it in Visual Studio Code.
7. Open `Project02-Part01-DataCleaning.ipynb`.
8. Select a Python kernel that has pandas installed.
9. Complete and run every notebook section.
10. Complete `AI-Use-Report.md`.
11. Commit and push your latest work.

## Data Files

Do not overwrite the four original CSV files:

- `CCM Computing Entry Survey - Fall 2020 (1).csv`
- `CCM Computing Entry Survey - Fall 2021.csv`
- `CCM Computing Literacy Course Entry Survey - Fall 2020.csv`
- `CCM Computing Literacy Course Entry Survey - Fall 2021.csv`

## Required Work

Your notebook must use pandas to:

1. Read all four CSV files into separate DataFrames.
2. Explore each DataFrame using properties and built-in functions such as `.shape`, `.columns`, `.head()`, `.info()`, `.describe()`, value counts, and missing-value counts.
3. Show exploration results in separate notebook cells.
4. Rename columns using clear lowercase `snake_case` names.
5. Decide which features are useful for studying recruitment of new students.
6. Remove irrelevant or redundant features and explain your decisions.
7. Clean and condense inconsistent categories such as major and race/ethnicity.
8. Identify differences between the 2020 and 2021 versions of each survey.
9. Realign common features before combining years. Do not simply concatenate mismatched columns.
10. Add a year column so the source year remains identifiable.
11. Check duplicates, missing values, data types, category spelling, and unexpected values.
12. Create exactly two combined DataFrames.
13. Save them in `cleaned-data/` as:
    - `computer_literacy_cleaned.csv`
    - `entry_level_computing_cleaned.csv`
14. Read the saved files back into pandas and verify their shape and columns.

## Notebook Documentation

Use Markdown cells to include:

- Your name
- Date
- Assignment name
- Purpose of the notebook
- A short explanation before each major group of code cells
- Reasons for dropping, renaming, grouping, or realigning features
- A final summary of the cleaning decisions and limitations

All data operations must be performed with Python and pandas. Do not manually edit the CSV files in Excel or another spreadsheet application.

## Submission Checklist

Your GitHub repository must contain:

- Completed `Project02-Part01-DataCleaning.ipynb`
- Four original input CSV files
- Two cleaned output CSV files in `cleaned-data/`
- Completed `AI-Use-Report.md`

Run all cells from top to bottom before submitting. Confirm that the notebook displays its results and that the latest files appear on GitHub.

## Git Commands

```bash
git status
git add .
git commit -m "Complete Project 2 Part 1 data cleaning"
git push
```

## Blackboard Ultra Submission

Blackboard Ultra is the official submission location. Submit the required assignment materials and include the link to your public GitHub repository.

**Uploading work to GitHub alone does not count as submitting the assignment.**

## Grading — 20 Points

| Area | Points |
|---|---:|
| Load and explore all four datasets | 4 |
| Clean column names, values, missing data, and redundancies | 6 |
| Align and combine the two survey years correctly | 5 |
| Save and verify the two required cleaned CSV files | 3 |
| Notebook organization, Markdown documentation, and AI-use report | 2 |
| **Total** | **20** |

## Data Responsibility

Use the survey data only for this course. Do not add names or other identifying information to the repository. In reports and discussions, describe groups and patterns rather than attempting to identify individual respondents.
