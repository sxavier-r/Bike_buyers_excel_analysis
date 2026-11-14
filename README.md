# Bike_buyers_excel_analysis
An analysis on bike purchases in excel using Bike purchasing data\

# Bike Buyers Customer Analysis (Excel)

Which customers are most likely to buy a bike? An Excel analysis of 1,000 customers, with a cleaned dataset, formula-driven summary tables, and a dashboard with dropdown filters.

<img width="350" height="263" alt="{A4AA1A5C-9915-4A17-A769-967E0D433BA2}" src="https://github.com/user-attachments/assets/811df164-5fe3-4f58-82f9-188697af6ee6" />


## Data
Bike Buyers dataset https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx.
1,026 rows and 13 columns, reduced to **1,000 customers** after removing 26 duplicates. Each row is one customer (age, income, gender, commute distance, region, and whether they bought a bike). There is no revenue or date data.

## What I did
- Removed duplicates, checked for missing values, and standardised labels (Female/Male, Married/Single)
- Created an **Age Bracket** field (Young adult up to 30, Middle-aged 31–55, Older 56+) with a nested IF
- Summarised purchase rate, customer count, and average income with `COUNTIFS` and `AVERAGEIFS`
- Built a dashboard with KPI cards, charts, and dropdown filters (Region, Education, Marital Status, Gender)

## Key findings
- **48.1%** of customers bought a bike (481 of 1,000)
- **Middle-aged customers (31–55) buy most often:** 54.0%, vs 35.5% for under-31s and 31.6% for over-55s
- **Short commutes go with higher purchase rates:** about 55–59% under 5 miles, falling to 29.7% at 10+ miles
- Buyers earn slightly more on average ($57,963 vs $54,875), but the gap is small

## Limitations
Sample data; these are associations, not proof of cause. Group sizes differ, so rates are shown rather than counts.

## Files
- `Bike_Buyers_Dashboard_Clean.xlsx` — workbook (Dashboard, Analysis, Clean_Data, Raw_Data)
- `images/dashboard.png` — dashboard screenshot

Built with AI assistance (Claude) and reviewed by me.

Author: Undikeye Samson
