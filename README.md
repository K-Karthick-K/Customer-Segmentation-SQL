# Customer Segmentation Using SQL

Objective: 
Segment customers based on purchasing behavior and demographics to improve marketing strategies and business performance.

Key Steps
1. Data Cleaning: 
    Removed null values from critical columns like `Customer ID` and `Total Spend`.
    Standardized categorical data for easier processing.

2. Data Aggregation: 
    Aggregated metrics like:
      Total Spend per customer.
      Items Purchased.
      Average Days Since Last Purchase.
      Satisfaction Level.

3. Customer Segmentation:  
   Segmented customers into three groups:
   High Value: High spenders with frequent purchases.
   Moderate Value: Average spenders with regular purchases.
   Low Value: Minimal spending customers.

4. SQL Queries: 
   All SQL queries for data cleaning, aggregation, and segmentation are saved in `Segmentation_Queries.sql`.

Files:
1. `Customer_data.csv` - Original dataset.
3. `Customer_Segments_SQL.csv` - Final segmentation results.
4. `Segmentation_Queries.sql` - SQL commands used for the analysis.

Tools Used
SQLite: For executing SQL queries in Google Colab.
Google Colab: Cloud environment for running SQLite.

Results
Segmented customers into three actionable groups:
High Value Customers - Suitable for premium marketing strategies.
Moderate Value Customers - Ideal for regular campaigns.
Low Value Customers - Focus on re-engagement or minimal investment.

About
This project demonstrates SQL proficiency for customer segmentation and highlights the use of SQL queries for business analytics.
