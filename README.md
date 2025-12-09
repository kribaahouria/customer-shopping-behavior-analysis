#🛍️ Customer Shopping Behavior Analysis
A Data Analytics Project using Python, SQL, and Power BI

#📌 Project Overview

This project provides a complete analysis of 3,900 customer shopping transactions to understand purchasing behavior, product performance, demographic trends, and the impact of discounts and subscriptions.

Using Python, PostgreSQL, and Power BI, the project follows a full analytics workflow:

✔ Data Cleaning
✔ Feature Engineering
✔ Exploratory Data Analysis (EDA)
✔ SQL Business Insights
✔ Interactive Dashboard
✔ Actionable Recommendations

This repository demonstrates strong skills in data analytics, business intelligence, SQL querying, feature engineering, and data storytelling.


#🧹 1. Data Preparation & Cleaning (Python)

Performed comprehensive data preprocessing:

🔧 Data Cleaning

Handled 37 missing values in review ratings

Standardized column names to snake_case

Removed duplicates & corrected inconsistent values

Cleaned string formatting and category labels


✨ Feature Engineering

Created age_group using quantile-based binning

Added purchase_frequency_days metric

Dropped redundant fields such as promo_code_used

Generated customer segmentation features


#🛢️ Database Integration

The cleaned dataset was loaded into a PostgreSQL database using SQLAlchemy for structured analysis.

Notebook: notebooks/EDA_and_Cleaning.ipynb


#🛢️ 2. SQL Business Analysis (PostgreSQL)

Key insights were extracted using optimized SQL queries:

📊 Key Business Questions

Revenue comparison by gender

High-spending discount users

Top 5 products by average rating

Standard vs. Express shipping behavior

Subscribers vs. non-subscribers revenue

Discount-dependent products

Customer segmentation: New, Returning, Loyal

Top 3 products per category

Relationship between repeat buyers & subscription

Revenue contribution by age group

All queries: sql/business_queries.sql

#📊 3. Power BI Dashboard

A dynamic dashboard was created to visualize insights clearly and interactively.

Dashboard Pages

Customer Overview

Revenue & Sales Analysis

Discount & Shipping Behavior

Customer Segmentation

File: powerbi/dashboard.pbix

#📈 4. Key Insights

🧑‍🤝‍🧑 Customer Behavior

Adults and middle-aged groups generate the highest revenue

Express shipping users tend to purchase higher-value items

Loyal customers show stronger purchasing patterns

💰 Discount Insights

Some products rely heavily on discounts

Discounts boost volume but may reduce margin

Need for a refined pricing strategy

⭐ Product Performance

Certain categories consistently receive higher ratings

Best sellers can be better promoted in marketing campaigns

#🚀 5. Business Recommendations

📌 Increase Subscription Adoption

Exclusive offers

Loyalty points

Early access to new items

📌 Optimize Discount Strategy

Reduce dependency on discounts for certain products

Replace discounts with value-based promotions

📌 Improve Product Positioning

Promote top-rated products

Highlight best sellers during peak seasons

📌 Boost Customer Loyalty

Reward repeat buyers

Personalized offers based on purchase frequency
