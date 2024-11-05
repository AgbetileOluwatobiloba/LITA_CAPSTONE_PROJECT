## LITA Capstone Project
---

### Project 1: Sales Performance Analysis for a Retail Store
---

#### Tools: Excel, SQL, Power BI

This project offers a comprehensive sales performance analysis for a retail store, utilizing Excel, SQL, and Power BI for data exploration and visualization.

Key Steps:

Excel Analysis:

Leveraged pivot tables to summarize total sales by product, region, and month after the data was first cleaned.
Calculated metrics such as average sales per product and total revenue by region using Excel formulas.

SQL Queries:

- Extracted key insights from sales data:
- Retrieved total sales per product category.
- Counted the number of sales transactions per region.
- Identified the highest-selling product by total sales value.
- Calculated total revenue per product and monthly sales for the current year.
- Ranked top 5 customers by purchase amount.
- Calculated each region's percentage contribution to total sales.
- Identified products with no sales in the last quarter.

Power BI Dashboard:

Created an interactive dashboard to visualize findings, including a sales overview, top-performing products, and detailed breakdowns by product and region.

### Project 2: Customer Segmentation for a Subscription Service
---

#### Tools: Excel, SQL, Power BI

This project focuses on segmenting and analyzing customer data for a subscription service, with the aim of understanding customer behavior, tracking subscription types, and identifying key trends in cancellations and renewals.

Key Steps:

Excel Analysis:

- Used pivot tables to identify subscription patterns after the data was first cleaned.
- Calculated metrics such as average subscription duration and identified popular subscription types.
- Generated additional reports to provide insights into customer behavior.


Power BI Dashboard:

Built an interactive dashboard showcasing customer segmentation, cancellation trends, and subscription patterns with slicers for in-depth analysis.

SQL Queries:

- Conducted further analysis by querying the dataset to extract insights:
- Retrieved total customer count by region.
- Identified the most popular subscription type by customer count.
- Isolated customers who canceled within 6 months.
- Calculated the average subscription duration for all customers.
- Found customers with subscriptions over 12 months.
- Calculated total revenue by subscription type.
- Identified the top 3 regions by cancellation rates.
- Counted active and canceled subscriptions.

  ```SQL
  Select * from SalesData
	Product,
	SUM(Quantity) AS TotalSales
```

These projects illustrate the use of data analysis tools to derive actionable insights and build effective visualizations, providing valuable decision-making support for business operations.
