# bright-coffee-shop-case-study

Project Overview

This project analyzes historical sales data from Bright Coffee Shop to uncover trends, top-performing products, and opportunities for revenue growth.
It was created as part of a data analytics portfolio project, simulating a real-world business scenario where insights are presented to a new CEO. 
This project is part of the Data Analysis Bootcamp by Bright Light Academy which focuses on upskilling individuals on data analysis and visualisation.

Objectives

-Identify which products generate the most revenue
-Find the peak sales times throughout the day
-Analyze sales trends by month and store location
-Segment customers into spending buckets
-Provide recommendations to improve sales performance

Tools & Technologies

1. Miro -	Project planning and data architecture design
2. Snowflake -	SQL data processing and cleaning
3. Microsoft Excel -	Data analysis, PivotTables, and visualization
4. PowerPoint -  Presenting final insights to stakeholders

Key Insights

-Most Profitable Products: Coffee-based beverages and pastries drive the highest revenue.
-Peak Sales Hours: Mornings are the busiest, suggesting strong coffee and tea demand.
-Monthly Performance: Noticeable increase in sales during winter months.
-Top Store Locations: Hell's Kitchen overall performs better followed by Astoria then Lower Manhattan.
-Customer Segmentation: Higher-spending customers purchase premium drinks and add-on snacks more frequently.

Recommendations
* Run morning promotions to capture high - traffic breakfast customers
* Restock best-sellers more frequently to avoid missed sales
* Promote underperforming products with bundle deals or discounts
* Use loyalty programs to retain top spenders

  
Data Processing Steps

1. Data Cleaning in Snowflake
   -Converted Excel dataset to CSV
   -Fixed inconsistent unit_price entries (e.g., '3,1' → 3.1)
2. Created new columns:
   - total_revenue = unit_price * transaction_qty
   - transaction_time_bucket (grouped sales by 1-hour intervals)
   - created time and spenders buckets
3. Data Export
  -Exported the transformed data back to Excel for pivot tables and graphs
