Customer Shopping Behaviour Analysis

## Overview
This project analyzes customer shopping behaviour using Python, MySQL, and Power BI to uncover trends in purchases, revenue, and customer segments.

## Dataset
- **Source:** [GitHub - amlanmohanty1](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI)
- **Records:** 3900+ customers
- **Features:** 18 columns including Age, Gender, Item Purchased, Category, Purchase Amount, Location, Season, Review Rating, Subscription Status, Payment Method, and more.

## Tools Used
| Tool | Purpose |
|------|---------|
| Python (Pandas) | Data loading & Exploratory Data Analysis |
| MySQL Workbench | Data storage & SQL queries |
| Power BI | Interactive dashboard & visualizations |

## Project Steps
1. Loaded dataset from GitHub using Python & Pandas
2. Connected Python to MySQL database using SQLAlchemy
3. Imported data into MySQL (`customer_shopping` database)
4. Ran 10 SQL queries for business analysis
5. Built interactive Power BI dashboard

## SQL Queries Covered
1. Total revenue by Male vs Female customers
2. Customers who used discount but spent above average
3. Top 5 products with highest average review rating
4. Average purchase amount by shipping type
5. Subscribed vs non-subscribed customer spending
6. Top 5 products with highest discount percentage
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 most purchased products per category
9. Repeat buyers vs subscription likelihood
10. Revenue contribution by age group

## Power BI Dashboard Includes
- 📊 Revenue by Category (Bar Chart)
- 🥧 Subscription Status (Pie Chart)
- 💰 Average Purchase Amount (Card)
- ⭐ Average Review Rating (Card)
- 🔘 Gender Filter (Slicer)
- 🔘 Subscription Status Filter (Slicer)

## Files in this Repository
| File | Description |
|------|-------------|
| `customer_shopping_analysis.ipynb` | Jupyter Notebook with Python code |
| `customer_queries.sql` | All 10 MySQL queries |
| `customer_shopping_dashboard.pbix` | Power BI Dashboard file |

## How to Run
1. Clone this repository
2. Open `customer_shopping_analysis.ipynb` in Jupyter Notebook
3. Run all cells to load and explore data
4. Open `customer_queries.sql` in MySQL Workbench and run queries
5. Open `customer_shopping_dashboard.pbix` in Power BI Desktop

## Author
**Monak**  
First Data Analytics Project 🚀
