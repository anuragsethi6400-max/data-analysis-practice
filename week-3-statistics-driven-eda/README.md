# Week 3: Statistics-Driven Titanic EDA

This project analyzes Titanic survival patterns using Python, pandas, seaborn, and basic statistical reasoning.

The focus is not only on finding survival rates, but also on checking whether findings are reliable, weak, or confounded.

## What I Worked On

- Distribution analysis
- Quantiles and outlier detection
- Survival-rate comparison
- Passenger-count reliability checks
- Weak vs strong findings
- Correlation vs causation
- Confounding between fare and passenger class
- Final EDA report with visual evidence

## Key Findings

1. Sex and passenger class were the strongest survival signals.
   First-class females had a 96.81% survival rate with 94 passengers, while third-class males had a 13.54% survival rate with 347 passengers.

2. Children had higher survival rates, but age-based findings need care.
   Children had a 57.97% survival rate with 69 passengers, while seniors had a 26.92% survival rate with only 26 passengers.

3. Fare was related to survival, but it was confounded by passenger class.
   Very-high-fare passengers had a 58.11% survival rate overall, but third-class very-high-fare passengers had only a 19.51% survival rate.

## Main Learning

A good analysis checks whether a pattern is supported by enough data and whether another feature may explain the result.

## Files

- `statistics_driven_titanic_eda.ipynb` - main notebook
- `titanic_features.csv` - cleaned Titanic dataset with engineered features