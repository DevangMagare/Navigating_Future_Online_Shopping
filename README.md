# Navigating_Future_Online_Shopping

📊 Navigating_Future_Online_Shopping Project (Python & SQL)
🔍 Project Overview

This project analyzes an e-commerce dataset to extract business insights using SQL (MySQL) and Python (Pandas & Matplotlib).
The goal is to understand customer behavior, sales performance, retention patterns, and overall business trends.


🛠️ Tools & Technologies Used

SQL: MySQL Workbench

Python: Pandas, Matplotlib

Notebook: Jupyter / Google Colab

Data Format: CSV files

📁 Dataset Description

The project uses a multi-table Online_Shopping dataset containing:

Customers

Orders

Order Items

Payments

Products

Sellers

Geolocation

The dataset represents real-world online shopping transactions and customer activity.

🧩 SQL Analysis (MySQL)
✔ Basic Analysis

Customers distribution by state

Orders count by year

Total sales by product category

✔ Intermediate Analysis

Monthly sales trends

Seller-wise revenue analysis

Average order value

✔ Advanced Analysis

Cumulative monthly sales

Year-over-Year (YoY) sales growth

Customer retention rate (within 6 months)

Top 3 customers by total spending

📌 Key Insight:
Customer retention was calculated using customer_unique_id instead of customer_id to correctly identify repeat customers.

🐍 Python Analysis (Pandas & Matplotlib)

Python was used for data exploration and visualization, not database operations.

Key Tasks:

Loading and exploring datasets using Pandas

Analyzing customer and order patterns

Visualizing trends using bar charts and line plots

Understanding cumulative sales and growth trends

Visualizations Include:

Customers by state

Orders per year

Monthly order trend

Top product categories by revenue

Top sellers by revenue

Cumulative sales over time

📈 Key Business Insights

Majority of customers are one-time buyers

Customer retention within 6 months is low (~2.3%)

A small number of customers contribute significantly to revenue

Sales show clear seasonal and yearly trends

📂 Project Structure
📁 Navigating_Future_Online_Shopping
│
├── 📄 Navigating_Future_Online_Shopping_Internship.ipynb
├── 📄 SQL_Queries.sql
├── 📄 customers.csv
├── 📄 orders.csv
├── 📄 order_items.csv
├── 📄 products.csv
├── 📄 sellers.csv
├── 📄 payments.csv
├── 📄 geolocation.csv
└── 📄 README.md

🚀 How to Run the Project

Clone the repository

Open the Jupyter Notebook (.ipynb) in Jupyter or Google Colab

Upload all CSV files, Link In Word File

Run cells sequentially

For SQL:

Import CSV files into MySQL

Run queries in MySQL Workbench

🎯 Learning Outcomes

Hands-on experience with real-world data

Strong understanding of SQL joins, aggregations, and window functions

Practical use of Python for data analysis & visualization

Ability to derive and explain business insights

👤 Author

Devang Magare
