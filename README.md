# customer_behavior_analysis
Data Analysis project showcasing cusotmer behavior analysis using python SQL and powerBI.
Overview

# This project demonstrates an end-to-end data analytics workflow starting from raw data to business insights.
## The process includes:

Loading the dataset in Python
Performing Exploratory Data Analysis (EDA)
Cleaning and transforming data
Running SQL queries in relational databases
Building an interactive Power BI dashboard
Writing a business report
Creating a presentation using Gamma

The goal of this project is to convert raw data into clear, actionable insights for decision-making.

# Dataset

Source: Replace with your dataset source
Format: CSV / Excel / Database Table

Example Dataset Fields
Customer ID
Product Name
Sales
Region
Order Date
Profit

# The dataset contains structured records used for analysis and visualization.

# Tools Used
Tool	Purpose
Python	Data loading, cleaning, EDA
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
PostgreSQL / MySQL / SQL Server	SQL analysis
Power BI	Dashboard creation
Microsoft Word / PDF	Reporting
Gamma	Presentation slides
Project Steps
# 1. Data Loading

Loaded the dataset into Python using Pandas.

import pandas as pd
df = pd.read_csv("dataset.csv")
# 2. Exploratory Data Analysis (EDA)

Performed initial analysis to understand:

Data types
Missing values
Summary statistics
Distribution patterns
Correlations

Example:

df.info()
df.describe()
# 3. Data Cleaning

Cleaned the dataset by:

Removing duplicates
Handling missing values
Correcting data types
Standardizing column names

Example:

df.drop_duplicates(inplace=True)
df.fillna(method='ffill', inplace=True)
4. SQL Analysis

Imported the cleaned dataset into:

PostgreSQL
MySQL
SQL Server

Used SQL queries to extract business insights.

Example:

SELECT region, SUM(sales) AS total_sales
FROM sales_data
GROUP BY region
ORDER BY total_sales DESC;
5. Power BI Dashboard

# Created an interactive dashboard containing:

KPI cards
Sales trends
Regional performance
Product analysis
Customer insights

# Dashboard allows stakeholders to explore data visually.

Dashboard

Main dashboard features include:

Monthly sales trend
Top-performing products
Region-wise performance
Profit analysis
Filters for dynamic exploration

## Results

Key outcomes from the analysis:

Identified top revenue regions
Found best-selling products
Detected low-performing segments
Improved data quality for reporting
Created a reusable analytics workflow

This project demonstrates both technical and business analysis skills.

## Report

A detailed report was created summarizing:

Problem statement
Methodology
Findings
Recommendations

The report supports business decision-making using data.

## Presentation

A professional presentation was created using Gamma to communicate:

Project objectives
Process
Insights
Final recommendations

Author
Vinay Dobriyal
Data Analytics Project Portfolio

Final Note

This project highlights practical experience in:

* Python analytics
* SQL querying
* Business intelligence
* Reporting
* Presentation skills
