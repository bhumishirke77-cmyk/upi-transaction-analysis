# UPI Transaction Analysis (2021–2022)

Exploratory data analysis on UPI transaction data across Indian banks.

## Dataset
- Source: [Kaggle] transaction data
- Two CSVs merged into a single dataframe
- Covers 19 months (Jan 2021 – Jul 2022)
- Columns: Bank name, transaction volume (Mn), transaction value (Cr), month, year

## What I did
- Merged two CSV files using pandas
- Cleaned bank name inconsistencies and handled null values
- Converted value columns to numeric for aggregation
- Built GroupBy aggregations — bank-wise and year-wise totals
- Created matplotlib visualizations including grouped bar charts and year-over-year comparison

## Tools Used
Python · pandas · matplotlib

## Key Findings
- PhonePe and Paytm dominated transaction volume across both years
- 2021 data covers 12 months vs 7 months in 2022
- Total transaction value grew significantly from 2021 to 2022
