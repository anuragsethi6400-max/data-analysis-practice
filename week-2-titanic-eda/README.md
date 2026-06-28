# Week 2: Titanic Data Cleaning and EDA

This folder contains my Week 2 work for the Titanic dataset. The goal was to move beyond basic pandas practice and build a cleaner, more structured exploratory data analysis workflow.

## What I Worked On

- Checked missing values, data types, duplicate rows, and unique values.
- Created a missing value strategy for important columns.
- Dropped `cabin` because it had too many missing values for this analysis.
- Filled missing `age` values using median age grouped by `sex` and `pclass`.
- Filled missing `embarked` values using the most common value.
- Created useful features: `family_size`, `is_alone`, `title_group`, `age_group`, and `fare_group`.
- Compared survival rates across important passenger groups.
- Built a final EDA report focused only on the strongest patterns.

## Files

- `titanic_cleaning_advanced.ipynb`: Main cleaning, feature engineering, and survival pattern notebook.
- `titanic_eda_report.ipynb`: Final report that turns exploration into a clear data story.
- `titanic_cleaned.csv`: Cleaned Titanic dataset.
- `titanic_features.csv`: Feature-engineered Titanic dataset.
- `notes.md`: Short learning notes and reflections.

## Main Findings

- Female passengers had much higher survival rates than male passengers.
- First-class passengers had better survival rates than second- and third-class passengers.
- Children had the highest survival rate among age groups.
- Higher fare groups had higher survival rates, likely because fare is connected to class and access.
- The strongest combined pattern was gender plus passenger class.

## What I Learned

EDA is not just making charts. A useful analysis should select the strongest patterns, explain why they matter, and avoid showing every possible table without a clear reason.

This week helped me understand how to clean data, engineer features, compare survival patterns, and write a focused report.
