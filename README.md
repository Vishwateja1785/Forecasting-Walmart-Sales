# Walmart Retail Sales Forecasting

## Project Overview
This project analyzes Walmart's weekly sales data to forecast future sales and identify key factors influencing sales performance. Using a dataset of over 450,000 weekly sales records, we examine the impact of various factors including markdowns, holidays, fuel prices, and temperature on sales across different Walmart stores.

## Key Features
- Time series analysis and forecasting of Walmart's retail sales data
- Examination of factors influencing sales:
  - Promotional markdowns
  - Holidays
  - Fuel prices
  - Temperature
- Utilization of PySpark for large-scale data processing
- Implementation of Facebook Prophet for time series forecasting

## Data
The dataset includes weekly sales data for 45 Walmart stores across the United States, featuring:
- Weekly sales figures per store and department
- Store information (size, type)
- Temperature data
- Fuel prices
- Promotional markdown data
- Economic indicators (CPI, unemployment rate)

## Methodology
1. Data Preparation: Merging multiple data files and cleaning the dataset
2. Exploratory Data Analysis: Identifying patterns and trends in sales data
3. Feature Analysis: Examining the impact of various factors on sales
4. Time Series Forecasting: Using Facebook Prophet to predict future sales
5. Distributed Computing: Leveraging PySpark for efficient processing of large-scale data

## Key Findings
- Seasonal patterns in sales, with higher sales towards year-end
- Significant impact of holidays on sales performance
- Varying effects of promotional markdowns on sales
- Influence of external factors like fuel prices and temperature on sales

## Technologies Used
- Python
- PySpark
- Facebook Prophet
- Pandas
- Matplotlib
