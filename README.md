# Pizza-Sales-Dashboard
🍕 Pizza Sales Analysis Dashboard (Power BI)
📌 Project Overview

The Pizza Sales Analysis Dashboard is a Business Intelligence project developed using Power BI to analyze pizza sales data and uncover meaningful business insights.

This dashboard helps businesses understand:

Overall sales performance

Customer ordering behavior

Best and worst selling pizzas

Revenue distribution by pizza category and size

Monthly and quarterly sales trends

The project demonstrates skills in data analysis, data modeling, DAX calculations, and interactive dashboard creation.

🎯 Project Objectives

The primary objectives of this project are:

Analyze overall pizza sales performance

Identify top-performing and low-performing pizzas

Understand customer purchase patterns

Evaluate revenue trends across time

Provide insights to support data-driven decision making

📊 Dashboard Pages

The Power BI report consists of two interactive dashboard pages:

1️⃣ Pizza Sales Overview Dashboard

This dashboard provides a high-level summary of pizza sales performance.

📈 Key Performance Indicators (KPIs)
Metric	Value
Total Revenue	817.86K
Total Orders	21K
Average Order Value	38.31
Total Pizzas Sold	50K
Average Pizzas per Order	2.32
📅 Total Orders by Day

This visualization shows daily order distribution.

Insights

Friday has the highest number of orders

Sunday has the lowest orders

📊 Total Orders by Month

This chart tracks monthly sales trends throughout the year.

Insights

Orders steadily increase throughout the year

Peak sales occur around mid-year months

📉 Total Revenue by Quarter

This visualization compares revenue performance by quarter.

Insights

Q2 generates the highest revenue

Slight decrease observed toward Q4

🍕 Revenue by Pizza Category

Pizza categories analyzed:

Classic

Supreme

Chicken

Veggie

Insights

Classic pizzas generate the highest revenue share

📏 Revenue by Pizza Size

Pizza sizes included in the analysis:

Small (S)

Medium (M)

Large (L)

Extra Large (XL)

XXL

Insights

Large pizzas contribute nearly 46% of total revenue

XXL pizzas contribute the least

🍕 Total Pizzas Sold by Category

Displays total quantity sold per category.

Insights

Classic pizzas are the most popular

Chicken pizzas have the lowest sales quantity

🏆 Best & Worst Sellers Dashboard

This dashboard identifies top and bottom performing pizzas based on revenue, orders, and quantity.

🔝 Top 5 Pizzas by Revenue

Highest revenue generating pizzas include:

The Thai Chicken Pizza

The Barbecue Chicken Pizza

The California Chicken Pizza

The Classic Deluxe Pizza

The Spicy Italian Pizza

🔝 Top 5 Pizzas by Total Orders

Most frequently ordered pizzas include:

Classic Deluxe Pizza

Hawaiian Pizza

Pepperoni Pizza

Barbecue Chicken Pizza

Thai Chicken Pizza

🔻 Bottom 5 Pizzas by Revenue

Lowest revenue generating pizzas include:

Brie Carre Pizza

Green Garden Pizza

Spinach Supreme Pizza

Mediterranean Pizza

Spinach Pesto Pizza

🔻 Bottom 5 Pizzas by Quantity

Least ordered pizzas include:

Brie Carre Pizza

Mediterranean Pizza

Calabrese Pizza

Soppressata Pizza

Spinach Supreme Pizza

🛠 Tools & Technologies Used
Tool	Purpose
Power BI	Dashboard Development
Power Query	Data Cleaning
DAX	Data Analysis
Excel / CSV	Dataset
SQL	Data Querying
📂 Project Structure
Pizza-Sales-PowerBI-Dashboard
│
├── Dataset
│   └── pizza_sales.csv
│
├── Dashboard
│   └── Pizza_Sales_Dashboard.pbix
│
├── Images
│   ├── sales_dashboard.png
│   └── best_worst_dashboard.png
│
├── SQL
│   └── pizza_sales_queries.sql
│
└── README.md
🧮 Key DAX Measures
Total Revenue
Total Revenue = SUM(pizza_sales[total_price])
Total Orders
Total Orders = DISTINCTCOUNT(pizza_sales[order_id])
Total Pizzas Sold
Total Pizzas Sold = SUM(pizza_sales[quantity])
Average Order Value
Avg Order Value = DIVIDE([Total Revenue], [Total Orders])
Average Pizzas per Order
Avg Pizzas Per Order = DIVIDE([Total Pizzas Sold], [Total Orders])
📊 Data Analysis Workflow

The project follows a standard data analytics workflow:

Data Collection

Data Cleaning (Power Query)

Data Modeling

DAX Calculations

Dashboard Development

Business Insights Generation

📸 Dashboard Preview
Sales Overview Dashboard
(Add screenshot here)
![Sales Dashboard](Images/sales_dashboard.png)
Best & Worst Sellers Dashboard
![Best Worst Dashboard](Images/best_worst_dashboard.png)
📈 Key Business Insights
1️⃣ Peak Sales Days

Friday and Thursday have the highest order volumes.

2️⃣ Best Performing Category

Classic pizzas generate the highest revenue and quantity sold.

3️⃣ Preferred Pizza Size

Large pizzas are the most preferred among customers.

4️⃣ Seasonal Sales Pattern

Sales gradually increase throughout the year with peak demand in mid-year months.

5️⃣ Underperforming Products

Certain pizzas consistently appear in bottom seller lists, indicating opportunities for menu optimization.

🚀 How to Use the Dashboard

Clone or download the repository

Open the Power BI (.pbix) file

Load the dataset if required

Explore the dashboard using slicers and filters

👨‍💻 Author

Praveen Kumar

Aspiring Data Analyst / Data Scientist
