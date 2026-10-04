# Retail Customer Analytics

A data analytics project focused on analyzing retail customer shopping behavior to identify purchasing patterns, customer preferences, and business insights using **Python, SQL, MySQL, and Power BI**.

## Objectives

* Clean and prepare retail customer data for analysis.
* Explore customer demographics and purchasing behavior.
* Analyze spending, purchasing, and product/category patterns.
* Perform data analysis using Python and SQL.
* Create an interactive Power BI dashboard.
* Generate insights that can support data-driven business decisions.

## Project Structure

```text
retail-customer-analytics/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── customer_shopping_behavior_cleaned.csv
│
├── python/
│   └── retail_customer_analytics.ipynb
│
├── sql/
│   └── customer_analysis.sql
│
├── power bi/
│   └── customer_behavior_dashboard
│
├── .gitignore
└── README.md
```

## Dataset

The project uses retail customer shopping behavior data.

* **`customer_shopping_behavior.csv`** — Original dataset.
* **`customer_shopping_behavior_cleaned.csv`** — Cleaned dataset prepared for analysis.

The data is inspected and cleaned before performing analysis to improve data quality and consistency.

## Python Analysis

The notebook `retail_customer_analytics.ipynb` contains the Python-based analysis, including:

* Data loading and inspection
* Data cleaning and preprocessing
* Exploratory data analysis
* Customer behavior analysis
* Data visualization
* Database connectivity

**Libraries:** Pandas, NumPy, Matplotlib, SQLAlchemy, and PyMySQL.

## SQL Analysis

`customer_analysis.sql` contains SQL queries used to analyze the customer data and extract meaningful information related to:

* Customer behavior
* Purchasing patterns
* Spending
* Products and categories
* Aggregated business metrics

The project uses **MySQL** for database analysis.

## Power BI Dashboard

The Power BI dashboard `customer_behavior_dashboard` presents the analysis through interactive visualizations.

It is designed to explore:

* Customer demographics
* Purchasing behavior
* Spending patterns
* Product/category trends
* Key business metrics

##  Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis
     ↓
SQL Analysis
     ↓
Business Insights
     ↓
Power BI Dashboard
```

## Tools & Technologies

**Python · Pandas · NumPy · Matplotlib · SQL · MySQL · SQLAlchemy · PyMySQL · Power BI · Jupyter Notebook · Git · GitHub**

## Key Insights

The analysis focuses on identifying patterns in:

* Customer purchasing behavior
* Spending patterns
* Product and category preferences
* Differences between customer groups
* Overall shopping trends

Specific numerical findings can be added here as the final analysis is completed.

## Security

The project uses a local `.env` file for MySQL credentials. The file is excluded from GitHub through `.gitignore` to prevent sensitive database information from being exposed.

