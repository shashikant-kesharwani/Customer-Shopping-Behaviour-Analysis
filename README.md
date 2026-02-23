# Customer-Shopping-Behaviour-Analysis
# Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The main objective is to uncover insights into customer spending patterns, product preferences, subscription behavior, and revenue contribution to support data-driven business decisions.
The project combines Python (Data Cleaning & EDA), SQL (Business Analysis), and Power BI (Dashboard Visualization) to deliver end-to-end data analysis.

# Dataset Summary
1. Total Records: 3,900
2. Total Columns: 18

# Key Features:
1. Customer demographics (Age, Gender, Location, Subscription Status)
2. Purchase details (Item Purchased, Category, Amount, Season, Size, Color)
3. Shopping behavior (Discount Applied, Frequency, Previous Purchases, Shipping Type, Review Rating)
4. Missing Values: 37 missing values in Review Rating column (handled during preprocessing)

# Data Cleaning & EDA (Python)
1. Performed data preprocessing and exploratory analysis using Python:
2. Imported dataset using pandas
3. Checked structure using df.info() and statistical summary using df.describe()
4. Handled missing values in Review Rating using median imputation (category-wise)
5. Standardized column names to snake_case
6. Created new features:
    i.  age_group (age binning)
    ii. purchase_frequency_days
7. Verified redundancy between discount_applied and promo_code_used
8. Integrated cleaned dataset into MySQL for SQL-based analysis

# SQL Business Analysis
Used SQL to answer key business questions:
1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top 5 highest-rated products
4. Shipping type vs purchase amount comparison
5. Subscribers vs non-subscribers revenue analysis
6. Most discount-dependent products
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Repeat buyers and subscription behavior
10. Revenue contribution by age group

# Power BI Dashboard
Built an interactive dashboard to visualize:
1. Revenue distribution
2. Customer segmentation
3. Product performance
4. Age-group contribution
5. Subscription impact
6. Shipping behavior insights
7. The dashboard provides clear and actionable insights for business stakeholders.













