# customer_behavior_analysis
Analyzed customer purchasing behaviour using Python and PostgreSQL, with insights shown through an interactive dashboard.

## Customer Behaviour Analysis Project

This project analyzes customer buying behaviour using Python, PostgreSQL, and a dashboard.
The goal is to understand how customers purchase products, how much they spend, and how different groups behave.

## Dataset

- 3,900 customer records
- Includes age, gender, product category, purchase amount, review rating, subscription status, and payment method

## Tools & Technologies

- Python (Pandas, NumPy)
- PostgreSQL
- Power BI Dashboard
- Visual Studio Code

## Data Cleaning & Feature Engineering

- Filled missing review ratings using category median
- Renamed columns to clean format
- Created age groups (Young Adult, Adult, Middle-Aged, Senior)
- Converted purchase frequency into numeric days
- Removed duplicate columns
- Loaded cleaned data into PostgreSQL

## SQL Analysis

- Customer purchases by season
- Average purchase amount
- Customer count by gender
- High-rating customers
- Revenue by product category
- Top customers by previous purchases
- Purchase frequency by age group
- Most used payment method by subscribers
- Item ranking using SQL window functions

## Dashboard Insights

- Average Purchase Amount
- Average Review Rating
- Total Customers
- Sales & Revenue by Category
- Subscription Status Distribution
- Sales & Revenue by Age Group

## Key Insights

- Clothing category generates the highest revenue
- Young Adult and Middle-Aged customers buy the most
- Average purchase amount is around $60
- Average customer rating is 3.75

## Project Outcome

- This project shows how Python + postgreSQL + Dashboard can be used together to analyze customer behaviour and support business decisions.
