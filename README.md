# Exploratory Data Analysis of Loan Application Data
## Introduction
This EDA is to explore the loan application data to see patterns of loan applicants.

## Data
This dataset was gotten from Kaggle. It contains 3000 rows and 20 columns. It is a loan application dataset that contains information about lenders':
**Personal information:** Age, Marital Status, Education Level, Employment Status, Job Tenure
**Financial status:** Annual Income, Monthly Income, Total Assets, Total Liabilities, Net Worth
**Credit behavior:** Credit Score, Credit Card Utilization, Debt-to-Income Ratio, Number of Credit Lines


Loan details: Loan Amount, Duration, Purpose, Interest Rate, Base Interest Rate


Behavioral history: Payment History, Bankruptcy History, Previous Defaults, Utility Bills Payment History

## Data Cleaning
I performed a data quality check to ensure it is clean and ready for analysis.
These were the data issues I found and rectified
1. **Missing Values**
I used ``` workers.isnull().sum() ``` to find the columns that had missing values and the total number of missing values. I found them in the following columns
