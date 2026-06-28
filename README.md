# Bank Marketing - Exploratory Data Analysis

## Overview
This project performs exploratory data analysis (EDA) on a bank marketing dataset to understand customer demographics, campaign details, and the likelihood of term deposit subscription.

## Dataset
- **File:** `bankmarketing.csv`
- **Rows:** 41,188
- **Columns:** 21
- **Target variable:** `y` (whether the client subscribed to a term deposit — yes/no)

## What This Notebook Covers
1. Loading and previewing the dataset
2. Checking for missing values and data types
3. Generating summary statistics for numerical and categorical columns
4. Visualizing the distribution of the target variable
5. Building a correlation matrix for numerical features
6. Drawing conclusions from the findings

## Key Findings
- No missing values in the dataset.
- The target variable is imbalanced: ~88.7% "no" vs ~11.3% "yes".
- Economic indicators (`emp.var.rate`, `euribor3m`, `nr.employed`) are strongly correlated with each other.
- Categorical features like `job`, `education`, and `poutcome` may be useful for segmentation in further modeling.

## Tools Used
- Python
- pandas
- seaborn
- matplotlib

## How to Run
1. Clone this repository.
2. Install the required libraries: `pip install -r requirements.txt`
3. Open `Bank_Marketing_Inspection_test.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells.

## Author
[Your Name]
