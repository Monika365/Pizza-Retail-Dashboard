# Pizza_Retail_Dashboard
 The goal of this project is to create an annual sales report for a pizza store using sales data from 2015, helping the owner understand customer behavior and sales trends to inform business decisions and future growth strategies
 
### 1.	🍕 Pizza Sales Analytics: Power BI Dashboard
A dynamic, interactive data visualisation dashboard designed to analyse and monitor pizza sales performance using SQL and Power BI—focusing on sales trends, product breakdowns, and actionable business insights.
### 2.	 Purpose
The Pizza Sales Analytics Dashboard is a visually engaging Power BI report that empowers users to explore, analyze, and compare pizza sales data from a full year of transactions. The dashboard highlights key metrics such as revenue, order trends, product performance, and customer preferences, enabling restaurant managers, analysts, and business owners to make informed decisions and optimize their strategies

### 3.	Tech Stack
List the key technologies used to build the dashboard.

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main data visualization platform for creating interactive reports and dashboards.

📂 Power Query – Used for data transformation, cleaning, and shaping before analysis in Power BI.

🧠 DAX (Data Analysis Expressions) – For calculated measures, KPIs, and dynamic visuals.

📝 SQL Server Management Studio (SSMS) – For initial data import, cleaning, and KPI calculation.

🔗 Data Modeling – Relationships established among tables (sales, products, orders) to enable cross-filtering and aggregation.

📁 File Format – .pbix for the Power BI dashboard, .csv for raw data, and .sql for query documentation

### 4.	Data Source
Source: Pizza sales data for the year 2015, provided as a CSV file and imported into SQL Server.

### 📂 Dataset Overview  
[![CSV File](https://img.shields.io/badge/View_Dataset-pizza_sales.csv-orange)](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/pizza_sales.csv)

This project is powered by a rich dataset containing **48,000+ rows** of pizza sales transactions 🍕📊—capturing real-world retail operations in detail.

- Covers order dates, pizza types, sizes, quantities, and revenue.
- Provides the foundation for uncovering trends in sales performance, customer preferences, and seasonal demand.
- Perfect for time series analysis, KPI tracking, and building end-to-end BI solutions.

> Dive into the data [here](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/pizza_sales.csv) and explore what’s driving those pizza profits!


Key fields: pizza_id, order_id, pizza_name_id, quantity, order_date, order_time, unit_price, total_price, pizza_size, pizza_category, pizza_name, and ingredients.

Data was cleaned and structured in SQL Server before being loaded into Power BI for visualization



### 5.	Highlights

•	Business Problem

Pizza restaurants accumulate vast amounts of transactional data, yet often lack effective tools to transform this information into actionable business insights. Key questions such as:

Which products generate the highest revenue? Identifying top-performing menu items is essential for optimizing offerings and maximizing profitability.

What are the busiest times and days for sales? Understanding peak periods helps with efficient staff scheduling, inventory planning, and targeted promotions.

Which pizza sizes and categories are most popular among customers? Analyzing preferences by size and type enables better menu design and marketing strategies.

These key questions are difficult to address using raw, unstructured data alone, highlighting the need for a comprehensive dashboard that delivers clear, data-driven insights

•	Goal of the Dashboard
To deliver an interactive, visual tool that:

Enables users to explore pizza sales data in depth.

Supports decisions on menu optimization, marketing, and inventory.

Uncovers trends in sales, product performance, and customer behavior

•	Walkthrough of Key Visuals
Key KPIs (Top Section)

Total Revenue

Average Order Value

Total Pizzas Sold

Total Orders

Average Pizzas per Order

•	Order Trend Visuals

Daily Trend: Bar chart showing total orders per day.

Monthly Trend: Line chart visualizing monthly order patterns.

•	Sales Breakdown

Donut Charts: Percentage of sales by pizza category and by pizza size.

Funnel Chart: Total pizzas sold by category.

•	Best & Worst Seller Analysis

Bar Charts: Top 5 and bottom 5 pizzas by revenue, quantity, and orders.

•	Interactive Filters

Slicers for pizza category and order date.

Action filters for dynamic drill-downs by day, product, or size.

•	Navigation

Buttons to switch between main dashboard and best/worst seller pages.

•	 Business Impact & Insights
Menu Optimization: Identify top and underperforming pizzas to refine offerings.

Marketing Focus: Target promotions based on peak sales periods and popular products.

Operational Efficiency: Align staffing and inventory with busiest times and days.

Strategic Planning: Leverage data-driven insights for long-term business growth.

### 6.	Screenshots 
Here Is My Dashboard
Homepage
You can view the main dashboard homepage here. 

![Home_preview](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/PizzaSalesHome.png)

Best/Worst Sellers
View the best and worst sellers dashboard here.

![best/worst_preview](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/Best%26worst.png)
