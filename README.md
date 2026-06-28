# Data Analysis Practice

Python, pandas, and data analysis notebooks from my AI/ML learning journey.

This repository tracks my practical work as I build toward machine learning: first Python and pandas foundations, then data cleaning, exploratory data analysis, visualization, and eventually model building.

## Repository Structure

| Folder | Focus | Main work |
|---|---|---|
| `week-1-python-pandas-basics/` | Python and pandas foundations | Python refresher, Kaggle pandas practice, basic Titanic analysis |
| `week-2-titanic-eda/` | Data cleaning and EDA | Missing values, feature engineering, survival pattern analysis, final EDA report |

## Week 1: Python and Pandas Basics

Covered:

- Python fundamentals: variables, functions, conditionals, loops, lists, dictionaries, imports
- pandas basics: DataFrames, Series, indexing, filtering, grouping, sorting, missing values, combining data
- Basic Titanic exploration using pandas
- Git, GitHub, and learning-in-public setup

Key notebooks:

- `week-1-python-pandas-basics/python_refresher.ipynb`
- `week-1-python-pandas-basics/pandas_basics_practice.ipynb`
- `week-1-python-pandas-basics/pandas_basics_titanic.ipynb`

## Week 2: Titanic Data Cleaning and EDA

Covered:

- Data quality checks: missing values, data types, duplicate checks, unique values
- Missing value strategy for `age`, `cabin`, and `embarked`
- Feature engineering: `family_size`, `is_alone`, `title_group`, `age_group`, and `fare_group`
- Survival rate analysis across gender, passenger class, age group, fare group, title group, and family status
- Visual storytelling with pandas, matplotlib, and seaborn
- Final EDA report focused on the strongest survival patterns

Key files:

- `week-2-titanic-eda/titanic_cleaning_advanced.ipynb`
- `week-2-titanic-eda/titanic_eda_report.ipynb`
- `week-2-titanic-eda/titanic_cleaned.csv`
- `week-2-titanic-eda/titanic_features.csv`

## Current Focus

I am moving from data analysis into beginner machine learning. The next step is to use the cleaned Titanic dataset to build a first supervised ML workflow with train/validation split, baseline models, evaluation metrics, and error analysis.
