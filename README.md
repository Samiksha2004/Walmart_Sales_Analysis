# Walmart_Sales_Analysis
End-to-end analysis of Walmart sales data using Python, MySQL . Cleaned and transformed data, engineered key metrics, and used SQL to extract insights on payment methods, product categories, and city-wise sales trends.

**Tech Stack:** Python • Pandas • SQL • MySQL 

## Overview

An end-to-end data analysis project focused on deriving actionable insights from Walmart’s transactional sales data. This project highlights the ability to transform raw data into meaningful outcomes through systematic data processing, database integration, and business-focused querying.

---

## Objectives

* Clean and preprocess transactional sales data using Python
* Engineer calculated fields such as total transaction value
* Load structured data into MySQL and PostgreSQL
* Write SQL queries to analyze business performance
* Extract insights on customer behavior, sales trends, and product performance

---

## Tools & Technologies

* **Languages:** Python, SQL
* **Libraries:** pandas, numpy
* **Databases:** MySQL
* **IDE:** Visual Studio Code
* **Data Source:** [Kaggle – Walmart Sales Data](https://www.kaggle.com/datasets)

---

## Project Structure

```
walmart-sales-analysis/
├── data/                # Raw & cleaned datasets
├── notebooks/           # Python EDA notebooks
├── sql_queries/         # Business-driven SQL scripts
├── main.py              # Core data processing script
├── requirements.txt     # Required Python libraries
└── README.md            # Project documentation
```

---

## Workflow Summary

### 1. Data Preparation

* Retrieved dataset via Kaggle API
* Inspected schema, cleaned duplicates, handled missing values
* Parsed price fields and corrected data types
* Created `total` column = `unit_price × quantity`

### 2. Database Integration

* Connected Python to **MySQL** and **PostgreSQL** using SQLAlchemy
* Created target tables and pushed cleaned data into both databases
* Validated database inserts via sample queries

### 3. Business Analysis via SQL

Executed well-structured SQL queries to analyze:

* Most frequent payment methods
* Revenue and sales by product categories
* Branch-wise and city-level performance
* Trends in customer quantity and transaction patterns

---

## Key Insights

* E-wallets had the highest transaction count
* Specific categories consistently outperformed others in revenue
* Certain cities showed strong, repeatable buying patterns
* Created a reliable analytical pipeline from raw data to decision-ready insights

---

## Potential Enhancements

* Integrate a visualization layer using Power BI or Tableau
* Automate pipeline for real-time data ingestion
* Combine with external datasets for deeper customer segmentation

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

* **Dataset**: Kaggle – Walmart Sales Dataset
* **Conceptual Inspiration**: Real-world business challenges in retail and operations analytics





