**🛍️ Project Title – Superstore Sales Analysis (SQL + Power BI)**

**📌 Overview**

This project demonstrates SQL and Power BI skills applied to a retail business scenario. The Superstore Sales Analysis project involves setting up a database using sales data, performing exploratory data analysis (EDA), and solving real-world business problems using SQL. The results are visualized through an interactive Power BI dashboard to uncover insights on customer behavior, product performance, regional profitability, and sales trends.

**🔍 Problem Statement**

Store businesses often struggle with tracking profitability, customer segmentation, and product performance across regions. This project addresses the need for data-driven decision-making by analyzing sales, profit margins, customer orders, and geographical insights to assist business strategy.

**📊 Tools & Technologies Used**

MySQL – Data cleaning, transformation, and business analysis

Power BI – Interactive data visualizations and dashboard

**📁 Dataset**

Database: Super_Store_db
Source: Publicly available Superstore sales dataset (e.g. Kaggle)
Key Columns:

order_id, order_date, ship_date, ship_mode

customer_id, customer_name, segment, state, city, country, market, region

product_id, product_name, category, sub_category

sales, quantity, discount, profit, shipping_cost, order_priority

**🧠 Approach**

Database Setup: Created and loaded Superstore sales data into MySQL

Data Cleaning: Removed records with missing/null values

Exploratory Data Analysis: Basic summaries and distribution checks

Business Querying: Wrote SQL queries to solve defined business problems

Dashboarding: Created a Power BI report to visualize KPIs, charts, and regional sales trends

**💼 Business Problem Statements & SQL Insights**

**1️⃣ Overview Metrics**

Total Customers, Orders, Sub-categories, Products

Total Sales, Total Profit, Total Cities

Average Discount

**2️⃣ Sales Performance Analysis by Customer**

Customer count by category

First and last order per customer

Year-wise sales trends

Customer segmentation based on sales

**3️⃣ Sales Analysis by Product & Sub-Category**

Top 50 products by sales and quantity

Sub-categories with sales > 1,000,000

Quantity sold per product

**4️⃣ Profitability & Area Analysis**

Profit margin by category and sub-category

Impact of discount on profit

Cumulative profit using window functions

Quantity analysis by region

Sales analysis by country

**📈 Key Features in Power BI**

KPIs: Total Sales, Total Profit, Avg Discount

Drill-down charts by Category, Region, Segment

sales by country and region

Bar chart of Top 20 products by sales

Line charts for year-wise trends

Doughnut for profit and sales across categories

**✅ Results**

Identified sub-categories has highest sales  with phones

Found standard shipping has minimum average cost with maximum profit amount

West european region had high quantity sale but low margins

United states has highest sales by technology category

Clear seasonal trends in sales across years







