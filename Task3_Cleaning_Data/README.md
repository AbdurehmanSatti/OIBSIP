# Task 3: Cleaning Data

## Objective
Take a deliberately messy dataset and systematically clean it into an 
analysis-ready dataset, documenting every decision made along the way.

## Dataset
Titanic dataset (`tested.csv`) — passenger records including age, fare, 
class, cabin, and embarkation port.

## Tools Used
Python, pandas, numpy, Jupyter Notebook

## What This Notebook Covers
- Initial data quality report (nulls, duplicates, dtype issues, value ranges)
- Missing data handling (median imputation for Age/Fare, 'Unknown' category for Cabin)
- Duplicate detection (none found, formally verified)
- Standardization (Embarked port codes converted to full names)
- Outlier detection using the IQR method (retained, as they reflect real passengers)
- Data type correction (PassengerId as string, categorical columns properly typed)
- Before vs. after summary table
- Cleaned dataset saved as `titanic_cleaned.csv`

## Key Decisions
- Median imputation used over mean for Age/Fare due to right-skewed distributions
- Cabin's 78% missing values were preserved as an 'Unknown' category rather than dropping rows
- Outliers (elderly passengers, high fares) were retained as genuine data, not errors

## How to Run
1. Clone this repository
2. Open `AbdurRehman_Task3.ipynb` in Jupyter Notebook
3. Ensure `tested.csv` is in the same folder
4. Run all cells in order