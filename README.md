# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project

   🔍 Overview

This project is an end-to-end, company-level data analytics project designed to replicate how data analysts work in real business environments. The objective is to analyze customer shopping behavior and generate actionable insights to improve sales, customer engagement, and marketing strategies.

The project follows the complete analytics lifecycle:
Business Understanding → Data Cleaning → SQL Analysis → Dashboarding → Reporting → Presentation

   🧠 Business Problem

A retail company wants to understand changes in customer purchasing behavior across:

Demographics

Product categories

Discounts & promotions

Shipping preferences

Subscription status

Key Question:

How can customer shopping data be leveraged to identify trends, improve customer engagement, and optimize business decisions?

   🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & feature engineering

PostgreSQL – Business analysis using SQL

Power BI – Interactive dashboard creation

GitHub – Project versioning & portfolio presentation

   📊 Dataset Description

Each row represents a customer’s most recent purchase, including:

Demographics (age, gender)

Product details (category, size, color)

Purchase behavior (amount, discounts, shipping)

Loyalty indicators (previous purchases, frequency)

Subscription & payment information

⚠️ Note: The dataset provides a behavioral snapshot, not full transaction history — similar to real corporate constraints.

   🔧 Data Cleaning & Feature Engineering

Performed in Python:

Handled missing review_rating using category-wise median imputation

Standardized column names using snake_case

Created new features:

age_group

purchase_frequency_days

Removed redundant columns after validation

Notebook:
📁 notebooks/01_data_cleaning_eda.ipynb

   🧮 SQL Business Analysis

Key business questions answered using SQL:

Revenue by gender

High-spending customers using discounts

Top-rated products

Subscription vs non-subscription behavior

Customer segmentation (New / Returning / Loyal)

Top products per category (window functions)

   SQL file:
📁 sql/business_analysis_queries.sql

📈 Power BI Dashboard

An interactive dashboard built for management decision-making:

KPI cards (customers, avg spend, ratings)

Revenue & sales analysis

Customer segmentation

Fully interactive slicers

Files:

📁 dashboard/customer_behavior_dashboard.pbix

📁 dashboard/dashboard_screenshots/

📑 Reporting & Presentation

Project Report: Technical documentation for internal use

Presentation Deck: Stakeholder-ready insights summary

Files:

📁 report/customer_behavior_analysis_report.pdf

📁 presentation/customer_behavior_presentation.pdf

   🚀 Key Business Insights

Express shipping customers spend more on average

Loyal customers form the majority of the revenue base

Several products rely heavily on discounts

Subscription adoption among repeat buyers is relatively low

   📌 How to Use This Repository

Review the business problem in this README

Explore Python EDA notebook

Check SQL queries for analysis logic

View dashboard screenshots or open .pbix

Read final insights in the presentation

 📎 Author

Merlyn V
B.Tech CSE (Health Informatics)
Aspiring Data Analyst | SQL | Python | Power BI
