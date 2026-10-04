# CMP 262 — Project 1: Fall 2026 Survey Data Cleaning

## Objective

Use pandas to explore and clean two current CCM computing survey datasets. The purpose is to prepare reliable, analysis-ready data that can support a future study of student recruitment and enrollment.

The two populations are:

- Students pursuing computing majors
- Students in computing literacy courses who are not pursuing computing majors

## Getting Started

1. Select **Use this template → Create a new repository**.
2. Choose your personal GitHub account as the owner.
3. Name the repository `LastName-FirstName-CMP262-Project01`.
4. Set the repository to **Public** and create it.
5. Clone **your new repository**, not the instructor repository.
6. Open the cloned folder in Visual Studio Code.
7. Open `Project01-DataCleaning.ipynb`.
8. Select a Python kernel with pandas installed.
9. Complete and run every notebook section.
10. Complete `AI-Use-Report.md`.
11. Commit and push your latest work.
12. Submit the public GitHub repository link through Blackboard Ultra.

## Required Input Files

The `data/` folder contains:

- `Majors Survey Results - Fall 2026.csv`
- `Non-Majors Survey Results - Fall 2026.csv`

Do not overwrite or manually edit the original CSV files.

## Required Work

Use pandas to complete the following work:

1. Read both CSV files into separate DataFrames.
2. Explore shape, columns, sample rows, data types, missing values, duplicates, and important category counts.
3. Show exploration results in separate notebook cells.
4. Rename columns using clear lowercase `snake_case` names.
5. Identify unusual text or inconsistent spelling and correct it with pandas when appropriate.
6. Select features that are useful for studying recruitment and enrollment.
7. Remove irrelevant or redundant features and explain your decisions.
8. Clean and condense inconsistent values, including major and race/ethnicity categories when appropriate.
9. Compare the majors and non-majors survey columns using pandas.
10. Keep each population in its own cleaned DataFrame.
11. Validate shapes, columns, missing values, duplicates, data types, and category values.
12. Save the two cleaned datasets in `cleaned-data/`.
13. Read the saved files back into pandas and verify them.

## Required Output Files

- `cleaned-data/majors_survey_cleaned.csv`
- `cleaned-data/nonmajors_survey_cleaned.csv`

Create both files with pandas using `to_csv(..., index=False)`.

## Notebook Documentation

Use Markdown cells to include:

- Your name, date, assignment name, and notebook purpose
- An explanation before each major group of code cells
- Reasons for dropping, renaming, grouping, or realigning features
- A final summary of cleaning decisions and remaining limitations

All required data operations must be performed with pandas. You are not expected to use NumPy, regular expressions, custom classes, or another data-analysis library. Do not manually clean the data in Excel or Google Sheets.

## Submission Checklist

Your repository must contain:

- Completed `Project01-DataCleaning.ipynb`
- Two original CSV files in `data/`
- Two cleaned CSV files in `cleaned-data/`
- Completed `AI-Use-Report.md`

Run all cells from top to bottom before submitting. Confirm that the latest notebook and output files appear on GitHub.

## Git Commands

```bash
git status
git add .
git commit -m "Complete Project 1 data cleaning"
git push
```

## Blackboard Ultra Submission

Blackboard Ultra is the official submission location. Include the link to your public GitHub repository.

**Uploading work to GitHub alone does not count as submitting the assignment.**

## Grading — 20 Points

| Area | Points |
|---|---:|
| Load and explore both datasets | 4 |
| Clean columns, encoding, missing data, categories, and redundancies | 7 |
| Compare structures and prepare two analysis-ready datasets | 4 |
| Save and verify both required cleaned CSV files | 3 |
| Notebook documentation and AI-use report | 2 |
| **Total** | **20** |

## Data Responsibility

Use the survey data only for this course. Do not add names or other identifying information. Discuss groups and patterns rather than attempting to identify individual respondents.
