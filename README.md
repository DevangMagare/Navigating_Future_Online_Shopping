# Navigating_Future_Online_Shopping

Navigating the Future of Online Shopping
SQL & Python Internship Project
Project Overview

This project focuses on analyzing a real-world Online Shopping (E-commerce) dataset to extract meaningful business insights using SQL (MySQL) and Python (Pandas & Matplotlib).

The main objective of this project is to understand customer behavior, sales performance, customer retention patterns, and overall business trends by answering analytical questions using SQL and validating insights through Python-based analysis and visualization.

Tools & Technologies Used

🔹SQL: MySQL Workbench

🔹Python: Pandas, Matplotlib

🔹Notebook Environment: Jupyter Notebook / Google Colab

🔹Data Format: CSV files

Dataset Description

The project uses a multi-table Online Shopping dataset consisting of the following files:

🔹Customers

🔹Orders

🔹Order Items

🔹Payments

🔹Products

🔹Sellers

🔹Geolocation

This dataset represents real-world e-commerce transactions, including customer details, order history, product information, seller data, and payment records.

SQL Analysis (MySQL)

SQL was used to perform structured data analysis by writing queries across multiple tables using joins, aggregations, and window functions.

Basic Analysis

🔹Customer distribution by state

🔹Number of orders by year

🔹Total sales by product category

Intermediate Analysis

🔹Monthly sales trends

🔹Seller-wise revenue analysis

🔹Average order value calculation

Advanced Analysis

🔹Cumulative monthly sales

🔹Year-over-Year (YoY) sales growth

🔹Customer retention rate within 6 months

🔹Top 3 customers by total spending

Important Note:
Customer retention was calculated using customer_unique_id instead of customer_id to correctly identify repeat customers across multiple orders.

Python Analysis (Pandas & Matplotlib)

Python was used for data exploration and visualization, not database operations.
The purpose of Python analysis was to visually validate and support insights derived from SQL.

Key Tasks Performed

🔹Loading and exploring datasets using Pandas

🔹Cleaning and transforming data where required

🔹Analyzing customer and order patterns

🔹Creating visualizations for trend analysis

Visualizations Included

🔹Customers by state

🔹Orders per year

🔹Monthly order trends

🔹Top product categories by revenue

🔹Top sellers by revenue

🔹Cumulative sales over time

🔹Customer retention visualization

Key Business Insights

🔹Majority of customers are one-time buyers

🔹Customer retention within 6 months is low (approximately 2.3%)

🔹A small percentage of customers contribute significantly to total revenue

🔹Sales show clear seasonal and yearly trends

🔹Identifying high-value customers and sellers can help improve business strategy

Project Structure

The project consists of the following files:

🔹Navigating_Future_Online_Shopping_Internship.ipynb
Contains complete Python analysis and visualizations.

🔹SQL_Queries.sql
Includes all SQL queries used for basic, intermediate, and advanced analysis.

🔹customers.csv
Customer-level information including location data.

🔹orders.csv
Order details such as order dates and status.

🔹order_items.csv
Product-level details for each order including price.

🔹products.csv
Product and product category information.

🔹sellers.csv
Seller-related details.

🔹payments.csv
Payment values and transaction details.

🔹geolocation.csv
Geographical information of customers.

🔹README.md
Project documentation and explanation.

How to Run the Project
Python

🔹Clone the repository

🔹Open the Jupyter Notebook (.ipynb) in Jupyter Notebook or Google Colab

🔹Upload all CSV files in the same directory

🔹Run the notebook cells sequentially

SQL

🔹Import CSV files into MySQL

🔹Open MySQL Workbench

🔹Execute SQL queries from the provided SQL file

Learning Outcomes

🔹Hands-on experience with real-world e-commerce data

🔹Strong understanding of SQL joins, aggregations, and window functions

🔹Practical experience using Python for data analysis and visualization

🔹Ability to derive, validate, and explain business insights

Author

Devang Magare
