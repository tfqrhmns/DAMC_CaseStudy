# DAMC_CaseStudy
# Sales Analysis Dashboard

This project presents an analysis of sales data with a focus on identifying performance by product line, understanding sales trends over time, and evaluating the impact of deal sizes on overall revenue. The data has been cleaned, transformed, and prepared for visualization in Looker Studio.

# Objectives

1. Identify which product lines have the highest and lowest sales.
2. Analyze sales trends over time to detect any seasonal or recurring patterns.
3. Examine how deal sizes (Small, Medium, Large) correlate with total sales and their percentage contribution.

# Data Cleaning Steps

- Created a new column `TOTALSALES` calculated as `QUANTITYORDERED * PRICEEACH`.
- Converted `ORDERDATE` to datetime format.
- Removed duplicate rows.
- Added `YEAR_MONTH` column to support monthly trend analysis.
- Verified the dataset is free from missing/null values.

# Key Insights

- **Classic Cars** product line recorded the highest sales, while **Trains** had the lowest.
- Sales peaked consistently in **October–November**, suggesting a strong seasonal effect.
- **Large deals** contributed the majority of total revenue, indicating the importance of high-value transactions.

## Tools Used

- Python (pandas, matplotlib)
- Google Looker Studio (for interactive dashboards)

## Output

A cleaned CSV file (`sales_cleaned.csv`), .ipynb file, and pdf dashboard ready for dashboard development and further exploration

For educational and portfolio use only.

Creator
Muhamad Taufiq Rahman Somantri
muhamadtaufiqrahmansomantri@gmail.com
