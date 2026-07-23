# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

Customer Shopping Behavior Analysis is an end-to-end Data Analytics project that analyzes customer purchasing patterns using transactional data. The project combines **Python, MySQL, and Power BI** to clean, analyze, and visualize customer behavior, enabling data-driven business decisions.

The objective is to identify customer trends, product performance, spending behavior, subscription patterns, and revenue opportunities.

---

## 🎯 Objectives

- Analyze customer purchasing behavior.
- Clean and preprocess real-world transactional data.
- Perform business analysis using SQL.
- Build an interactive Power BI dashboard.
- Generate actionable business recommendations.

---

## 📊 Dataset Information

- **Total Records:** 3,900
- **Total Features:** 18

### Dataset includes:

- Customer Demographics
  - Age
  - Gender
  - Location
  - Subscription Status

- Purchase Information
  - Item Purchased
  - Category
  - Purchase Amount
  - Season
  - Color
  - Size

- Shopping Behavior
  - Discount Applied
  - Previous Purchases
  - Frequency of Purchases
  - Review Rating
  - Shipping Type
  - Payment Method

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI

---

# 📂 Project Workflow

## 1. Data Cleaning & Preprocessing (Python)

- Imported dataset using Pandas
- Handled missing values
- Renamed columns to snake_case
- Feature Engineering
  - Created Age Groups
  - Created Purchase Frequency feature
- Removed redundant columns
- Loaded cleaned data into PostgreSQL

---

## 2. SQL Business Analysis

The following business questions were answered using PostgreSQL:

- Revenue by Gender
- High Spending Discount Users
- Top 5 Highest Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Analysis
- Discount Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyers Analysis
- Revenue by Age Group

---

## 📈 Power BI Dashboard

![Dashboard](Dashboard@01.png)

The dashboard provides interactive insights including:

- Total Customers
- Average Purchase Amount
- Average Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution
- Interactive Filters

---

# 💡 Key Business Insights

- Male customers generated higher overall revenue.
- Loyal customers formed the largest customer segment.
- Clothing category contributed the highest revenue.
- Express shipping users showed higher average purchase amounts.
- Top-rated products can be promoted for better conversions.
- Subscription users provide consistent business value.

---

# 📢 Business Recommendations

- Increase subscription membership through exclusive offers.
- Reward loyal customers with loyalty programs.
- Optimize discount strategies to improve profit margins.
- Promote top-rated and best-selling products.
- Target marketing campaigns based on age groups and purchasing behavior.

---

# 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
├── Python/
│   ├── data_cleaning.ipynb
│   └── analysis.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Dashboard Screenshots/
│
├── README.md
└── requirements.txt
```

---

# 🚀 Future Improvements

- Customer Lifetime Value (CLV) Prediction
- Customer Churn Prediction
- Product Recommendation System
- Sales Forecasting
- Interactive Web Dashboard using Streamlit

---

## 👨‍💻 Author

**Parth K. Tiwari**

LinkedIn: https://www.linkedin.com/in/parth-k-tiwari-579b46293/

GitHub: https://github.com/parthtiwari038

