# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior data for a retail company to uncover trends, understand purchase patterns, and generate actionable business insights. The analysis combines Python for data cleaning and exploratory data analysis (EDA), SQL for structured querying and business analysis, and Power BI for interactive dashboard creation.

The project was developed to answer the following business question:

> “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

---

# Project Objectives

* Clean and prepare raw customer shopping data
* Perform exploratory data analysis (EDA)
* Build SQL-based business insights and customer analytics
* Create an interactive Power BI dashboard
* Generate recommendations for improving sales and customer engagement

---

# Dataset Information

The dataset contains customer shopping behavior information including:

* Customer demographics
* Product categories
* Purchase amounts
* Seasonal trends
* Review ratings
* Discounts and promo code usage
* Payment methods
* Purchase frequency
* Subscription status

### Dataset Size

* **Rows:** 3,900
* **Columns:** 18

### Key Features

| Column                 | Description                  |
| ---------------------- | ---------------------------- |
| Customer ID            | Unique customer identifier   |
| Age                    | Customer age                 |
| Gender                 | Customer gender              |
| Item Purchased         | Product purchased            |
| Category               | Product category             |
| Purchase Amount (USD)  | Transaction value            |
| Season                 | Purchase season              |
| Review Rating          | Customer review score        |
| Discount Applied       | Whether discount was applied |
| Promo Code Used        | Promo code usage             |
| Previous Purchases     | Number of previous purchases |
| Payment Method         | Customer payment preference  |
| Frequency of Purchases | Purchase frequency           |

---

# Project Structure

```bash
├── customer_shopping_behavior.csv      # Raw dataset
├── EDA.ipynb                           # Python EDA and preprocessing notebook
├── final_db.sql                        # SQL queries and database operations
├── Customer_Behavior dashboard.pbix    # Power BI dashboard file
├── Business Problem Document.pdf       # Problem statement and deliverables
└── README.md                           # Project documentation
```

---

# Technologies Used

## Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Database

* PostgreSQL
* SQLAlchemy
* Psycopg2

## Visualization

* Power BI

---

# Data Preparation & Cleaning

The dataset was cleaned and transformed using Python.

### Tasks Performed

* Checked for missing values
* Standardized column names
* Verified data types
* Removed duplicates
* Performed exploratory analysis
* Prepared data for SQL import and dashboarding

---

# Exploratory Data Analysis (EDA)

Key analyses performed in the notebook include:

* Customer demographics analysis
* Revenue distribution analysis
* Seasonal purchasing trends
* Category-wise sales performance
* Discount impact on purchases
* Payment method preferences
* Subscription behavior analysis
* Customer review trends

---

# SQL Analysis

The cleaned dataset was imported into PostgreSQL for structured querying.

### SQL Operations Included

* Table creation
* Data insertion
* Aggregate analysis
* Customer segmentation
* Revenue analysis
* Loyalty analysis
* Purchase behavior analysis

### Example Insights

* High-spending customer segments
* Most profitable product categories
* Frequently used payment methods
* Impact of discounts on purchase frequency
* Repeat customer behavior patterns

---

# Power BI Dashboard

An interactive Power BI dashboard was developed to visualize customer behavior and business insights.

### Dashboard Features

* KPI cards for total revenue and customer metrics
* Sales trend visualizations
* Category-wise revenue charts
* Customer demographic filters
* Seasonal analysis
* Interactive slicers and drill-downs

### Business Value

The dashboard helps stakeholders:

* Monitor customer trends
* Identify profitable categories
* Understand customer preferences
* Improve marketing strategies
* Support data-driven decision making

---

# Key Business Insights

Some important insights derived from the project:

* Discounts and promo codes influence purchase decisions significantly
* Certain product categories perform better during specific seasons
* Subscription customers show stronger repeat purchase behavior
* Payment method preferences vary across customer groups
* Customer reviews can help identify satisfaction trends

---

# Recommendations

Based on the analysis, the following recommendations were made:

1. Increase targeted promotional campaigns during high-performing seasons
2. Personalize offers based on customer purchase history
3. Focus marketing efforts on loyal and subscription-based customers
4. Improve customer engagement using review and feedback analysis
5. Optimize inventory planning according to seasonal demand trends

---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone <repository-link>
cd customer-shopping-behavior-analysis
```

## 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

## 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
EDA.ipynb
```

## 4. Run SQL Scripts

Import the dataset into PostgreSQL and execute:

```sql
final_db.sql
```

## 5. Open Power BI Dashboard

Open the `.pbix` file using:

* Microsoft Power BI Desktop

---

# Future Improvements

* Add machine learning models for customer segmentation
* Build sales forecasting models
* Deploy dashboard online using Power BI Service
* Integrate real-time transaction data
* Perform sentiment analysis on customer reviews

---

# Conclusion

This project demonstrates how retail customer data can be transformed into meaningful business insights using Python, SQL, and Power BI. The analysis helps businesses better understand customer behavior, improve engagement strategies, and make informed decisions for long-term growth.

---

# Author

AKSHYAT BORA

---

# License

This project is for educational and portfolio purposes.
