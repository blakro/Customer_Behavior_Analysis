# Customer Shopping Behavior Analysis

## Overview
This project provides a comprehensive analysis of customer shopping behavior using a multi-tool approach. The goal is to extract actionable insights from retail data to help businesses understand customer demographics, purchasing patterns, and the effectiveness of loyalty programs. The project covers the entire data lifecycle: from raw data cleaning in Python to advanced querying in SQL and interactive visualization in Power BI.

## Dataset
The analysis is based on the **Customer Shopping Behavior Dataset**, which contains 3,900 records of customer transactions.
- **Key Features:** Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Previous Purchases, Payment Method, and Frequency of Purchases.
- **Source:** `customer_shopping_behavior.csv`

## Tools
- **Python:** Data cleaning, preprocessing, and exploratory data analysis (EDA) using `pandas`.
- **SQL (PostgreSQL/MySQL):** Advanced data querying and business logic implementation.
- **Power BI:** Interactive dashboarding for stakeholder reporting.
- **Gamma:** AI-powered presentation generation for executive summaries.
- **Microsoft Word/PDF:** Detailed project reporting.

## Steps
1.  **Data Loading & Cleaning (Python):**
    - Handled missing values (e.g., Review Rating).
    - Standardized column names and data types.
    - Feature engineering: Created `age_group` and converted `frequency_of_purchases` into numerical `purchase_frequency_days`.
2.  **Exploratory Data Analysis (EDA):**
    - Analyzed distributions and correlations using Python.
3.  **Database Ingestion & SQL Analysis:**
    - Migrated cleaned data from Python to a PostgreSQL database using `SQLAlchemy`.
    - Executed complex queries to segment customers and analyze revenue drivers.
4.  **Data Visualization:**
    - Developed an interactive dashboard in Power BI to track KPIs.
5.  **Reporting:**
    - Compiled findings into a professional PDF report and a Gamma-powered PowerPoint presentation.

## Dashboard
![Customer Behavior Dashboard](https://via.placeholder.com/800x450.png?text=Add+Your+Dashboard+Screenshot+Here)
*Note: Open `customer_behavior_dashboard.pbix` in Power BI Desktop to interact with the full report.*

## Results
- **Customer Segmentation:** Identified key segments (New, Returning, Loyal) based on purchase history to target marketing efforts.
- **Revenue Drivers:** Pinpointed high-performing product categories and locations.
- **Discount Impact:** Analyzed how promotional offers correlate with purchase frequency and total spend.
- **Subscription Analysis:** Evaluated the behavior of subscribed vs. non-subscribed customers to optimize loyalty programs.

## How to Run

### 1. Prerequisites
- Python 3.x
- PostgreSQL or MySQL
- Power BI Desktop

### 2. Python Environment Setup
Install the required libraries:
```bash
pip install pandas sqlalchemy psycopg2
```

### 3. Data Processing
Run the Jupyter Notebook to clean the data and export it to your database:
```bash
jupyter notebook customer_behavior.ipynb
```
*Note: Update the database connection string in the notebook with your credentials.*

### 4. SQL Analysis
Import the `customer_shopping_behavior.sql` file into your SQL editor (pgAdmin, MySQL Workbench, etc.) to run the analytical queries.

### 5. View Dashboard
Open `customer_behavior_dashboard.pbix` using Power BI Desktop.

---
**Deliverables:**
- 📄 [Project Report (PDF)](./Customer_Shopping_Behavior_Analysis_Report.pdf)
- 📊 [PowerPoint Presentation](./Customer-Shopping-Behavior-Analysis.pptx)
- 💾 [SQL Queries](./customer_shopping_behavior.sql)
- 📓 [Python Notebook](./customer_behavior.ipynb)
