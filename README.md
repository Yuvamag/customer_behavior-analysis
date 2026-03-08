# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using a dataset of 3,900 retail transactions.  
The goal is to identify purchasing patterns, customer segments, and product preferences to generate actionable business insights.

The project demonstrates a complete **data analytics workflow**, including data cleaning, exploratory analysis, SQL-based business queries, and dashboard visualization.

---

## Dataset Summary

- **Total Records:** 3,900
- **Total Features:** 18

### Key Data Categories

**Customer Demographics**
- Age
- Gender
- Location
- Subscription Status

**Purchase Information**
- Item Purchased
- Category
- Purchase Amount (USD)
- Season
- Size
- Color

**Shopping Behavior**
- Discount Applied
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

---

## Project Workflow

### 1. Data Cleaning & Preprocessing (Python)
Performed using **Python and Pandas** in Jupyter Notebook.

Key steps included:
- Loading and exploring the dataset
- Handling missing values
- Standardizing column names
- Creating new features (age groups, purchase frequency)
- Removing redundant columns
- Preparing the dataset for SQL analysis

---

### 2. Exploratory Data Analysis
Initial analysis was performed to understand:
- Customer demographics
- Spending patterns
- Product popularity
- Purchase trends

---

### 3. SQL Business Analysis
The cleaned dataset was analyzed using **SQL queries in Microsoft SQL Server** through **SQL Server Management Studio (SSMS)**.

Key business questions explored:

- Revenue comparison by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type spending comparison
- Subscribers vs non-subscribers purchasing behavior
- Customer segmentation (New, Returning, Loyal)
- Top products per category
- Revenue contribution by age group

---

### 4. Data Visualization
An interactive dashboard was created using **Power BI** to visualize insights including:

- Revenue distribution
- Customer demographics
- Product category performance
- Shopping behavior trends

---

## Tools & Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Power BI

---

## Business Insights

The analysis helps businesses:

- Identify high-value customer segments
- Understand purchasing patterns
- Improve product marketing strategies
- Optimize discount policies
- Enhance customer loyalty programs

---

## Repository Structure

```
customer-shopping-behavior-analysis
│
├── notebooks
│   └── 01_customer_shopping_data_cleaning.ipynb
│
├── sql
│   └── business_analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.png
│
└── README.md
```
