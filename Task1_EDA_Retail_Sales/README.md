# Task 1: EDA on Retail Sales Data

## Objective
Perform exploratory data analysis on a retail sales dataset to uncover sales 
trends, customer patterns, and product performance, and translate the findings 
into actionable business recommendations.

## Dataset
Superstore-style retail sales dataset (`train.csv`), containing order details, 
customer segments, regions, product categories, and sales figures.

## Tools Used
Python, pandas, matplotlib, seaborn, Jupyter Notebook

## What This Notebook Covers
- Initial data inspection (shape, data types, missing values)
- Descriptive statistics on Sales
- Monthly and quarterly sales trend analysis
- Customer distribution by Segment and Region
- Top 10 best-selling products and revenue by category
- Correlation heatmap (Sales vs. Shipping Days)
- Average order value by sub-category
- Business recommendations based on the findings

## Key Findings
- Sales are highly seasonal, peaking in Q4 every year
- A small number of high-value products (e.g. copiers) drive a large share of revenue
- Shipping time has no meaningful correlation with order value
- Consumer segment and the West region lead in order volume

## How to Run
1. Clone this repository
2. Open `AbdurRehman_Task1.ipynb` in Jupyter Notebook
3. Ensure `train.csv` is in the same folder
4. Run all cells in order