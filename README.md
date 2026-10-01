# Customer_Behavior_Analysis
Data analytics project showcasing customer behavior analysis using python, sql and power bi.
# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across different product categories.

The main goal of this project is to understand:

* Customer spending patterns
* Customer segments
* Product preferences
* Subscription behavior
* Discount usage
* Revenue trends

The analysis was performed using **Python, PostgreSQL (SQL), and Power BI** to generate meaningful business insights.

---

## 📊 Dataset

* **Rows:** 3,900
* **Columns:** 18
* **Missing Values:** 37 values in the `Review Rating` column

### Key Features

* Customer demographics – Age, Gender, Location, Subscription Status
* Purchase details – Item Purchased, Category, Purchase Amount, Season, Size, Color
* Shopping behavior – Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

---

## 🐍 Data Cleaning & Exploratory Data Analysis

Python was used for data cleaning, preparation, and exploratory analysis.

### Steps Performed

* Loaded the dataset using **Pandas**
* Checked dataset structure using `df.info()`
* Generated summary statistics using `df.describe()`
* Checked and handled missing values
* Filled missing Review Ratings using the **median rating of each product category**
* Standardized column names using snake_case
* Created an `age_group` feature
* Created `purchase_frequency_days`
* Checked data consistency between discount and promo code columns
* Removed the redundant `promo_code_used` column

---

## 🗄️ SQL Analysis

The cleaned data was loaded into **PostgreSQL** for business transaction analysis.

### Business Questions Answered

1. Revenue comparison by gender
2. High-spending customers who used discounts
3. Top 5 products based on average ratings
4. Standard vs Express shipping comparison
5. Subscribers vs Non-Subscribers spending analysis
6. Products with the highest percentage of discounted purchases
7. Customer segmentation into New, Returning, and Loyal customers
8. Top 3 products in each category
9. Relationship between repeat purchases and subscription
10. Revenue contribution by age group

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** was created to visually present the key insights from the analysis.

The dashboard helps understand customer behavior, revenue patterns, product performance, and subscription trends.

---

## 💡 Business Recommendations

Based on the analysis:

* **Boost Subscriptions:** Promote exclusive benefits for subscribers.
* **Customer Loyalty Programs:** Reward repeat buyers and encourage them to become loyal customers.
* **Review Discount Policy:** Balance discounts with profit margins.
* **Product Positioning:** Promote top-rated and best-selling products.
* **Targeted Marketing:** Focus marketing efforts on high-revenue age groups and express-shipping users.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **PostgreSQL**
* **SQL**
* **Power BI**
* **Jupyter Notebook**

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
└── README.md
```

---

## 🎯 Project Outcome

This project demonstrates an end-to-end **Data Analytics workflow**:

**Data Cleaning → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights**

The project helped identify customer behavior patterns and translate data into actionable business insights.

