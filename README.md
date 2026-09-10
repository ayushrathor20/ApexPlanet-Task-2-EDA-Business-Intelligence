# ApexPlanet Task 2 – EDA & Business Intelligence

## Project Overview

This project is part of the ApexPlanet Software Pvt Ltd Data Analytics Internship.

The objective of Task 2 is to perform Exploratory Data Analysis (EDA), answer business questions using SQL, analyze relationships between variables, and create a static business dashboard.

## Dataset

The analysis uses the cleaned sales dataset prepared during Task 1.

Dataset contains 1000 sales records and 15 columns, including:

- Order_ID
- Customer_ID
- Customer_Name
- Gender
- Age
- City
- Product
- Category
- Quantity
- Unit_Price
- Total_Sales
- Order_Date
- Year
- Month
- Month_Name

## Task 2 Analysis

### 1. Descriptive Statistics & Univariate Analysis

Performed:

- Numerical descriptive statistics
- Categorical analysis
- Histograms
- Bar charts
- Top cities and products analysis

### 2. SQL Business Analysis

Five business questions were answered using SQL:

1. What is the total sales revenue generated?
2. Which product category generates the highest revenue?
3. Which products generate the highest revenue?
4. How does revenue change month by month?
5. Which customers generate the highest revenue?

SQL queries and query results are included in the `sql/` folder.

### 3. Multivariate Analysis

Performed:

- Correlation matrix
- Correlation heatmap
- Quantity vs Total Sales scatter plot
- Unit Price vs Total Sales scatter plot
- Relationship analysis between numerical variables

### 4. Static Sales Dashboard

The dashboard includes:

- Total Revenue
- Total Orders
- Total Customers
- Total Units Sold
- Revenue by Category
- Monthly Sales Trend
- Top Products by Revenue
- Revenue by Gender
- Top Cities by Revenue
- Key Business Insights

## Key Business Insights

- Electronics is the highest-revenue category.
- Laptop is the highest-revenue product.
- March is the highest-sales month.
- Patna is among the top-performing cities by revenue.
- Total revenue generated is approximately ₹13.94 crore.

## Project Structure

```text
ApexPlanet-Task-2-EDA-Business-Intelligence/
│
├── data/
│   └── Cleaned_ApexPlanet_Sales_Dataset.xlsx
│
├── notebook/
│   └── EDA_Business_Analysis.ipynb
│
├── sql/
│   ├── SQL_Business_Questions.sql
│   └── SQL_Query_Results.xlsx
│
├── visualizations/
│   └── EDA_Charts.zip
│
├── dashboard/
│   └── ApexPlanet_Task2_Sales_Dashboard.xlsx
│
└── README.md
