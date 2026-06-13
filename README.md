# 📌 📊 Customer Behavior Analysis (SQL + Python + EDA)
🧠 Project Overview

This project analyzes customer behavior data to understand purchasing patterns, sales distribution, and customer segmentation.
It combines SQL for data handling, Python (Pandas) for data cleaning, and Matplotlib for visualization.

The goal is to extract meaningful business insights from raw customer transaction data.
📂 Dataset Information

The dataset contains customer purchase details with features such as:

- Customer demographics: `age`, `gender`, `age_group`, `location`
- Purchase details: `item_purchased`, `category`, `purchase_amount`
- Behavior features: `frequency_of_purchases`, `previous_purchases`
- Marketing factors: `discount_applied`, `subscription_status`
- Product attributes: `size`, `color`, `season`
- Transaction info: `payment_method`, `shipping_type`

# ⚙️ Technologies Used
Python 🐍
Pandas 📊
Matplotlib 📈
PostgreSQL 🗄️
SQL 🧾
VS Code 💻

# 🧹 Data Cleaning Process
Removed duplicate records
Handled missing values
Standardized categorical values
Created derived columns like age_group
Prepared dataset for analysis using SQL + Python

# 🧮 SQL Operations
Extracted raw data from PostgreSQL
Performed grouping and aggregation
Queried sales and customer metrics
Joined and filtered data for analysis


# 📊 Key Visualizations
1. Subscription Status Distribution
Pie chart showing % of subscribed vs non-subscribed customers
![Subscription Status](visuals/subscription_status.png)
3. Sales by Category
Bar chart showing which product categories generate highest revenue
4. Revenue by Age Group
Horizontal bar chart to identify high-value customer segments
