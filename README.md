# Pizza_Retail_Dashboard
 The goal of this project is to create an annual sales report for a pizza store using sales data from 2015, helping the owner understand customer behavior and sales trends to inform business decisions and future growth strategies
 
📊 Project Overview
Objective:
Build an interactive business intelligence dashboard that enables comprehensive analysis of:

Sales trends 📈

Customer demographics 👥

Product performance 🍕

Operational efficiency ⚙️

This allows stakeholders to make data-driven decisions for growth and optimization.

🗂️ Dataset Information
Source: Pizza Sales Transactional Dataset (CSV / SQL Database)
![csvfile](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/pizza_sales.csv)

Key Fields:

Pizza ID, Order ID, Order Date & Time, Quantity, Unit Price, Total Price

Pizza Size, Category, Ingredients, Pizza Name

Customer Info (Gender, Age, Location)

Sales Region, Order Status, Sales Channel

❓ Key Business Questions (KPIs Answered)
📆 Which month had the highest sales and orders?

🚻 Who purchases more – Men or Women?

📦 What are the different order statuses (delivered, cancelled, refunded)?

🏆 What are the top 10 states contributing to sales?

👥 What is the relation between age and gender on orders?

🌐 Which sales channel contributes the most?

🍕 What’s the highest selling pizza category?

✅ What percentage of orders are successfully delivered?

🔧 Project Workflow
1️⃣ Data Acquisition & Loading (SQL)
Imported raw data into SQL Server/MySQL/PostgreSQL.

Structured tables: Orders, Order Details, Pizzas, Customers, Sales Regions.

2️⃣ Data Cleaning & Transformation (SQL)
Removed duplicates, handled null values.

Normalized and joined related tables.

Calculated KPIs such as Total Sales, Average Order Value, and more.

Created views/tables for Power BI integration.

3️⃣ Data Analysis (SQL Queries)
Extracted:

Daily & Monthly Sales Trends

Category & Size Sales

Best & Worst Selling Pizzas

Customer Demographics

Sales Channel Performance

Order Fulfillment Metrics

4️⃣ Dashboard Creation (Power BI)
Imported clean datasets.

Designed interactive visualizations:

Bar, Line, Pie, Donut Charts

Maps for regional sales

Tables for top/bottom performers

Slicers for dynamic filtering (category, size, region, date, etc.)

📈 Dashboard Preview

KPIs Displayed: Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, Average Pizzas per Order.

Trends Visualized: Daily and monthly order trends, sales by category and size.

Performance Analysis: Best and worst sellers.

Filters: Interactive slicers for pizza category, size, region, and date range.

Here Is My Dashboard
Homepage
You can view the main dashboard homepage here. 

![Home_preview](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/PizzaSalesHome.png)

Best/Worst Sellers
View the best and worst sellers dashboard here.

![best/worst_preview](https://github.com/Monika365/Pizza_Retail_Dashboard/blob/main/Best%26worst.png)



🔎 Key Insights
Insight Area	Highlights
Sales vs. Orders	Peak months, sales volumes & order counts
Top Month	Identified highest sales/order month
Customer Demographics	Gender, age group analysis
Order Status	Delivered, Cancelled, Refunded, Returned
Top States	Top 10 states/regions driving sales
Sales Channels	Contribution by sales channels (e.g., online, in-store)
Best/Worst Sellers	Menu performance insights
Fulfillment Rate	Percentage of successful deliveries

📝 Conclusion
By combining SQL’s robust data processing with Power BI’s powerful visualizations, this project offers a comprehensive framework for sales performance tracking and business optimization.

✅ Data-driven insights can help:

Optimize product offerings 🍕

Target the right customer segments 🎯

Improve operational efficiencies ⚙️

Boost overall sales growth 🚀

🔗 Repository Content
SQL Scripts (Data Cleaning & Analysis)

Power BI Dashboard Files (.pbix)

Dataset Files (CSV/SQL format)

Visualizations

💡 Technologies Used
SQL Server / MySQL / PostgreSQL

Power BI Desktop

Excel (for initial data review)

GitHub

Final Conclusion
Leveraging SQL for robust data processing and Power BI for dynamic visualization provides a powerful framework for pizza sales analysis. Focusing marketing and operational strategies on high-performing customer segments, regions, and product categories—revealed by the dashboard—can drive future sales and business growth.




