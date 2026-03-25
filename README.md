# 🛍️ Customer Behavior Analysis & Revenue Insights

## 📌 Overview

This project focuses on analyzing customer shopping behavior to extract meaningful business insights. It involves data cleaning, feature engineering, SQL-based analytics, and dashboard visualization to support data-driven decision-making in retail.

## 🎯 Objectives

* Clean and preprocess raw customer transaction data
* Perform feature engineering for better analysis
* Store structured data in a PostgreSQL database
* Analyze customer behavior using SQL queries
* Generate insights on revenue, customer segmentation, and product trends
* Build a dashboard for visualization (Power BI)

## 📂 Dataset

* Contains customer demographics, purchase history, and transaction details
* Key features:

  * Age, Gender
  * Item Purchased, Category
  * Purchase Amount
  * Subscription Status
  * Discount Usage
  * Purchase Frequency

## 🛠️ Tech Stack

Python (Pandas, NumPy)
SQL (PostgreSQL)
SQLAlchemy
Power BI (Dashboard)
Jupyter Notebook

## 🔄 Data Processing Steps

1. Data Cleaning

* Handled missing values using median imputation
* Standardized column names
* Removed redundant columns (e.g., Promo Code)

### 2. Feature Engineering

* Created `age_group` (Young Adult, Adult, Middle-aged, Senior)
* Converted purchase frequency into numeric days
* Structured data for SQL analysis

### 3. Data Storage

* Loaded processed data into PostgreSQL using SQLAlchemy

## 📊 Key Business Questions Solved

* 💰 Revenue comparison between male vs female customers
* 🛒 Customers spending above average despite discounts
* ⭐ Top-rated products based on customer reviews
* 🚚 Impact of shipping type on purchase amount
* 📈 Do subscribed customers spend more?
* 🏷️ Products with highest discount usage
* 👥 Customer segmentation (New, Returning, Loyal)
* 🛍️ Top products within each category
* 🔁 Relationship between repeat buyers and subscriptions
* 👴 Revenue contribution by age group

## 📈 Insights Generated

* Identified high-value customer segments
* Found correlation between subscriptions and higher spending
* Highlighted top-performing products and categories
* Revealed discount effectiveness on sales

## 📊 Dashboard

* Built an interactive Power BI dashboard
* Features:

  * Revenue trends
  * Customer segmentation
  * Product performance
  * Filters for dynamic analysis

## 🧠 Learnings

* End-to-end data analytics workflow
* Data cleaning & feature engineering techniques
* Writing optimized SQL queries for business problems
* Building insights-driven dashboards


## 🚀 Future Improvements

* Add Machine Learning models for customer prediction
* Deploy dashboard as a web app (Streamlit)
* Integrate real-time data pipeline

## 📌 Conclusion

This project demonstrates how raw customer data can be transformed into actionable insights that help businesses improve revenue, customer retention, and product strategies.

---
