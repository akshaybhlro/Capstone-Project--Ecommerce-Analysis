# E-commerce Data Analysis - Capstone Project

## Overview
This project focuses on analyzing an e-commerce dataset to explore customer behavior, sales performance, and business trends.  
The process involves creating a relational database in MySQL, loading and cleaning data using Python, performing analysis in Jupyter Notebook, and building an interactive dashboard in Power BI.

---

## Project Workflow

### 1. Database Setup (MySQL)
Relational tables were designed for customers, products, orders, order items, and payments.  
The schema defines primary and foreign key relationships to ensure data consistency.  
**File:** `mysql/Project-Ecommerce_Analysis.sql`

### 2. Data Loading and Cleaning (Python & Jupyter)
Data was loaded into MySQL using Python and then processed in Jupyter Notebook for cleaning and exploration.  
Various charts were generated using pandas, matplotlib, and seaborn to identify key sales and customer trends.  
**Files:**  
- `python/load_sample_data.ipynb`  
- `python/Project-Ecommerce_Analysis.ipynb`

### 3. Dashboard Creation (Power BI)
A Power BI dashboard was developed to visualize insights such as:
- Total and average sales  
- Top-selling products  
- Customer purchasing patterns  
- Order and delivery performance  
**File:** `powerbi/Project-Ecommerce Analysis.pbix`

---

## Tools and Technologies
- MySQL  
- Python  
- Jupyter Notebook  
- Power BI  
- Libraries: pandas, matplotlib, seaborn, mysql-connector-python

---

## Business Insights
The analysis revealed that the e-commerce platform generated a total revenue of **$24 million** from a customer base of around **89,000 customers**.  
The **average order value** was approximately **$269**, indicating consistent purchase behavior among customers.  
The **Toys** category emerged as the top-performing segment, contributing nearly **$23 million** in revenue.  
Geographically, most of the orders were concentrated in the **São Paulo** region, highlighting it as the primary market focus.

---

## How to Run

### Tool Requirements
- **Database:** MySQL 8.0  
- **Analysis:** Python 3.x (pandas, numpy, matplotlib, seaborn, mysql-connector-python)  
- **Visualization:** Power BI Desktop  
- **IDE:** Jupyter Notebook, MySQL Workbench

### Steps
1. Run the SQL script:  
   `mysql/Project-Ecommerce_Analysis.sql`  
2. Load the data using:  
   `python/load_sample_data.ipynb`  
3. Open and execute:  
   `python/Project-Ecommerce_Analysis.ipynb`  
4. View the dashboard in Power BI:  
   `powerbi/Project-Ecommerce Analysis.pbix`

---

This project demonstrates a complete data analysis workflow — from database design to dashboard insights — showcasing how data can drive meaningful business decisions.
