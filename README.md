**Food Delivery Time & Delay Analysis**

Analyzing 1,000 food delivery records to uncover the key drivers of delivery delays and provide actionable business recommendations — using Microsoft Excel and Power BI.

## Problem Statement

Food delivery platforms face significant customer dissatisfaction due to unpredictable delays. This project investigates what factors most influence delivery time and delays, enabling data-driven decisions to improve operational efficiency.

## Objective

Identify the key factors contributing to food delivery delays and provide insights to help businesses optimize courier allocation, reduce delays, and improve customer satisfaction.


## Dataset Summary

Property              Details 

Total Records         1,000 
Total Columns         9 (5 Numerical, 4 Categorical) 
Missing Values        Handled 
Duplicate Records     0 

**Key Columns:** Order ID, Delivery Time, Distance, Weather Condition, Traffic Level, Time of Day, Vehicle Type, Courier Experience, Delay Status


## Tools Used

- **Microsoft Excel** — Data cleaning, preprocessing, EDA
- **Power BI** — Interactive dashboard and visualizations


## Methodology / Process

Raw Dataset
    |
Data Cleaning (Excel)
-> Removed nulls, standardized categories, validated data types
    |
Exploratory Data Analysis (Excel)
-> Identified distributions, outliers, and patterns
    |
Dashboard Creation (Power BI)
-> Built 8 interactive visual features with KPIs
    |
Insight Extraction & Business Recommendations


## Key Insights

- 41.5% of all orders were delayed — a critical operational issue
- High traffic caused the longest average delivery times
- Snowy weather resulted in the highest delay rates across all weather conditions
- Evening deliveries recorded the highest average delivery time of the day
- Longer distances directly correlated with increased delivery times
- Experienced couriers consistently delivered orders faster and more efficiently


## Dashboard Features

Feature                                               Description 

KPI Cards                     Total Orders, Avg Delivery Time, Avg Distance, Avg Prep Time, Delayed Orders 
Traffic Impact Analysis       Delivery time breakdown by traffic level 
Weather Impact Analysis       Delay rates across weather conditions 
Vehicle Type Performance      Comparison of delivery efficiency by vehicle 
Time of Day Analysis          Peak delay windows throughout the day 
Distance vs Delivery Time     Correlation scatter visual 
Courier Experience Analysis   Performance by experience level 
Delayed Orders by Traffic     Stacked breakdown of delays per traffic level 


## Business Recommendations

1. **Avoid peak evening slots** — Schedule more couriers during evening hours to handle demand surges
2. **Weather-based routing** — Implement dynamic ETA adjustments during snowy or rainy conditions
3. **Traffic-aware dispatch** — Use real-time traffic data to assign orders more efficiently in high-traffic zones
4. **Prioritize experienced couriers** for long-distance or high-value orders
5. **Distance thresholds** — Set realistic delivery radius limits to reduce delay risk


## Future Scope

- Extend analysis using Python (Pandas, Matplotlib, Seaborn) for deeper statistical modeling
- Build a machine learning model to predict delivery delays before dispatch
- Integrate real-time traffic API data for live delay prediction
- Expand dataset to include customer ratings and correlate with delay impact


## Files Included

File                        Description 

Food.pbix               Power BI Dashboard file 
cleaned data.xls        Cleaned and preprocessed dataset 
Dashboard.png           Dashboard preview screenshot 
Food.pdf                Project report 


## Dashboard Preview

![Dashboard](Dashboard.png)

 
