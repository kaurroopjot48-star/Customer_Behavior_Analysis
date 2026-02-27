📊 Customer Shopping Behavior Analysis
End-to-End Data Analytics Project | Python • PostgreSQL • Power BI • Business Insights
📌 Project Overview

This project performs a comprehensive end-to-end analysis of customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective of this project was to:

Analyze customer spending patterns

Understand product performance

Evaluate subscription impact on revenue

Identify high-value customer segments

Provide actionable business recommendations

This project demonstrates strong capabilities in:

Data Cleaning & Feature Engineering (Python)

Business-Driven SQL Analysis (PostgreSQL)

Data Visualization & Reporting (Power BI)

Strategic Thinking & Insight Communication

📂 Dataset Description

The dataset contains:

3,900 rows

18 columns

Customer demographics, transactional, and behavioral features

Key Variables Include:
🔹 Customer Demographics

Age

Gender

Location

Subscription Status

🔹 Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

🔹 Behavioral Attributes

Discount Applied

Promo Code Used

Previous Purchases

Frequency of Purchases

Review Rating

Shipping Type

Data Quality

37 missing values in review_rating

Handled via median imputation grouped by product category

Verified data consistency

Removed redundant columns

🛠 Tools & Technologies Used
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & exploratory analysis
PostgreSQL	Business SQL analysis
SQLAlchemy & psycopg2	Database integration
Power BI	Interactive dashboard creation
Jupyter Notebook	Development environment
Gamma	Presentation creation
Git & GitHub	Version control & project hosting
🔎 Project Workflow
1️⃣ Data Preparation & EDA (Python)
Data Loading

Imported dataset using pandas

Reviewed dataset structure with df.info()

Generated summary statistics using df.describe()

Data Cleaning

Identified and handled missing values

Standardized column names to snake_case

Checked for duplicates

Validated logical consistency between:

discount_applied

promo_code_used

Feature Engineering

Created age_group using age binning

Converted frequency text into numeric purchase_frequency_days

Engineered customer segments (New, Returning, Loyal)

Database Integration

Connected Python to PostgreSQL

Loaded cleaned DataFrame into relational database

Validated successful table creation

2️⃣ SQL Business Analysis (PostgreSQL)

Performed structured business analysis to answer real-world business questions.

Revenue Analysis

Revenue by gender

Revenue by age group

Revenue by subscription status

Revenue by product category

Customer Behavior Insights

Identified high-spending discount users

Analyzed repeat buyers and subscription correlation

Segmented customers into:

New

Returning

Loyal

Product Performance

Top 5 products by rating

Discount-dependent products

Top 3 products per category

Shipping type comparison

Subscription Insights

Compared subscriber vs non-subscriber:

Average spend

Total revenue

Repeat purchase behavior

📊 Power BI Dashboard

An interactive dashboard was created to visualize insights clearly for stakeholders.

Dashboard Highlights:

Total Customers: 3.9K

Average Purchase Amount: ~$59.76

Average Review Rating: 3.75

Revenue by Category

Revenue by Age Group

Subscription Distribution

Sales by Shipping Type

Interactive Filters:

Gender

Category

Subscription Status

Shipping Type

The dashboard allows business users to dynamically explore revenue patterns and customer behavior.

📈 Key Insights

Male customers generate 2.1x more revenue than female customers.

Clothing category contributes approximately 45% of total revenue.

839 customers used discounts but still spent above average — indicating discount does not necessarily reduce profitability.

Loyal customers represent the largest segment.

Express shipping customers spend slightly more on average.

Subscription revenue is significant but has growth opportunity.

💡 Strategic Business Recommendations
1️⃣ Boost Subscription Growth

Promote exclusive benefits and personalized offers to increase subscriber base.

2️⃣ Strengthen Loyalty Programs

Incentivize repeat buyers to move them into the Loyal segment.

3️⃣ Optimize Discount Strategy

Balance sales growth with margin protection.

4️⃣ Target High-Value Segments

Focus marketing efforts on:

High-revenue age groups

Express shipping customers

High-spending discount users

5️⃣ Product Positioning Strategy

Highlight top-rated and high-revenue categories in marketing campaigns.

▶️ How to Run This Project
🔹 Step 1: Python Environment Setup
pip install pandas numpy sqlalchemy psycopg2

Run Jupyter:

jupyter notebook

Execute notebook cells in order.

🔹 Step 2: PostgreSQL Setup

Create a new database in pgAdmin

Create table structure

Import cleaned CSV file

Execute SQL queries

🔹 Step 3: Power BI Dashboard

Connect Power BI to PostgreSQL

Load the cleaned dataset

Create measures & visualizations

Publish dashboard
📁 Project Structure
customer-shopping-analysis/
│
├── data/
│   └── customer_behavior.csv
│
├── notebooks/
│   └── customer_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── presentation/
│   └── customer_analysis_presentation.pptx
│
├── report/
│   └── project_report.pdf
│
└── README.md
🎯 What This Project Demonstrates

Strong SQL proficiency

Real-world business thinking

Data cleaning & feature engineering skills

BI dashboard development

End-to-end analytics pipeline understanding

Ability to convert raw data into strategic recommendations
