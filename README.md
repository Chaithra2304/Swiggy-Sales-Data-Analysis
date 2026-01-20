# Swiggy Sales Analysis
An end-to-end data analysis project on Swiggy food delivery data to identify sales trends, customer behavior, and business insights using SQL and Power BI.

## Business Problem
Swiggy operates across multiple cities with thousands of daily orders. 
The business needs insights into:
- Revenue trends
- High-performing cities and categories
- Customer spending behavior
- Rating patterns affecting sales

## Data Cleaning & Validation
- Checked for null values in critical columns
- Removed blank and empty strings
- Identified and removed duplicate records
- Ensured correct data types for dates and prices

## Data Modeling
Implemented a Star Schema for efficient analytics:

### Dimension Tables
- dim_date
- dim_location
- dim_restaurant
- dim_category
- dim_dish

### Fact Table
- fact_swiggy_orders1

## Key Performance Indicators (KPIs)
- Total Orders
- Total Revenue (INR)
- Average Dish Price
- Average Rating

## Analysis Performed

### Time-Based Analysis
- Monthly order trends
- Quarterly growth
- Year-wise performance

### Location-Based Analysis
- Top cities by orders
- Revenue contribution by city
- Top categories
- Most ordered dishes

### Customer Spend Analysis
- Spending buckets:
  - Under ₹100
  - ₹100–199
  - ₹200–299
  - ₹300–499
  - ₹500+

## Tools & Technologies
- SQL (Data cleaning & modeling)
- Power BI (Visualization & dashboards)
- Excel (Initial inspection)

## Key Insights
- Bengaluru generated the highest revenue
- Recommended category had the highest order volume
- Orders peak during mid-year months
- Higher-priced dishes generally received better ratings

## Conclusion
This project demonstrates how raw transactional data can be transformed into meaningful business insights using proper data modeling, KPI tracking, and visualization techniques.

## 👤 Author
Chaithra V | Data Analyst | LinkedIn: www.linkedin.com/in/chaithra-v-9babab351
