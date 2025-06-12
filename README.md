# CrustMetrics-A-Data-Driven-Approach-to-Pizza-Sales-Intelligence

CrustMetrics is a comprehensive business intelligence project that leverages Power BI and SQL to analyze and visualize key sales metrics for a fictional pizza chain. The project focuses on extracting actionable insights from sales data to enhance strategic decision-making in areas like product performance, customer preferences, and sales trends.

📊 Tools & Technologies
Power BI: Interactive dashboards, data visualizations, DAX measures

SQL (MySQL): Data querying, aggregation, and transformation

Data Source: Pizza Sales dataset (CSV format)

Visualization: KPI cards, bar charts, line graphs, donut charts, filters & slicers

📌 Key Features
📈 KPI Dashboard: Total Revenue, Total Orders, Average Order Value, Total Pizzas Sold, Average Pizzas per Order

📅 Time-Based Trends: Daily and Monthly sales trends for order tracking

🍕 Category Analysis: % Sales by Pizza Category and Pizza Size

🔝 Performance Analysis: Top & Bottom 5 pizzas by revenue, quantity, and total orders

🔍 Filter Functionality: Slicers for date range and pizza category for dynamic exploration

💬 Business Insights: Identifies best-selling pizzas, peak sales periods, and revenue-driving categories

🧠 SQL Query Highlights
All data transformations and KPIs were calculated using raw SQL before loading into Power BI:

Revenue & Order KPIs:

SELECT SUM(total_price) AS total_revenue FROM pizza_sales;

Average Order Value:

SELECT SUM(total_price)/COUNT(DISTINCT order_id) AS avg_order_value FROM pizza_sales;

Sales Breakdown by Category/Size:

SELECT pizza_category, SUM(total_price) AS revenue FROM pizza_sales GROUP BY pizza_category;
Full list of queries is included in the SQL queries.pdf file in this repo.


https://github.com/vinshijain8/CrustMetrics-A-Data-Driven-Approach-to-Pizza-Sales-Intelligence/blob/main/snapshot%20of%20dashboard%201.png

