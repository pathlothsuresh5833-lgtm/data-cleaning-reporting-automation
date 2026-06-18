# Data Cleaning & Reporting Automation

## Project Overview
This project focuses on automating data cleaning and reporting processes using Power BI. The dataset was cleaned, transformed, and analyzed using Power Query and DAX measures to generate interactive dashboards and business insights.

## Objectives
- Automate data cleaning processes.
- Handle duplicate records and data inconsistencies.
- Create interactive dashboards for reporting.
- Generate business insights through visual analytics.
- Improve reporting efficiency and decision-making.

## Tools Used
- Power BI
- Power Query
- DAX
- Sample Superstore Dataset

## Data Cleaning Activities
- Removed duplicate records.
- Checked and handled missing values.
- Standardized data types.
- Validated data quality and consistency.
- Automated transformation steps using Power Query.

## Dashboard Components

### KPI Cards
- Total Sales
- Total Profit
- Total Orders

### Visualizations
- Sales by Category
- Profit by Region
- Sales by Segment
- Monthly Sales Trend

## DAX Measures

### Total Sales
```DAX
Total Sales = SUM('Sample_superstore'[Sales])
```

### Total Profit
```DAX
Total Profit = SUM('Sample_superstore'[Profit])
```

### Total Orders
```DAX
Total Orders = DISTINCTCOUNT('Sample_superstore'[Order ID])
```

## Key Insights
- Technology category generated the highest sales.
- West region recorded the highest profit.
- Consumer segment contributed the largest share of sales.
- Monthly sales trends indicate steady business growth.
- Automated reporting improved efficiency and reduced manual effort.

## Benefits of Automation
- Faster report generation.
- Improved data accuracy.
- Reduced manual data processing.
- Enhanced business decision-making.
- Consistent and reliable reporting.

## Conclusion
The project successfully automated data cleaning and reporting processes using Power BI. The dashboard provides meaningful business insights and demonstrates how automation can improve reporting efficiency, data quality, and decision-making.

## Author
Veeramani Yelusuri

## Project Outcome
Developed an automated reporting solution that streamlines data preparation, visualization, and business analysis through Power BI.
