# 🛒 Customer Shopping Behavior Analysis

## 📌 Overview

This project analyzes customer shopping behavior using an end-to-end data analytics pipeline to uncover insights on spending patterns, customer segmentation, product preferences, and subscription behavior.

The goal is to transform raw transactional data into actionable business insights that can drive strategic decision-making.

---

## 🎯 Problem Statement

Businesses often lack clarity on:

* Which customers generate the most revenue
* How purchasing behavior varies across segments
* Whether subscription models are effective
* Which products drive engagement and sales

This project addresses these challenges using data-driven analysis.

---

## 🧠 Dataset Summary

* 📊 3,900 transactions
* 🧾 18 features
* ⚠️ 37 missing values (handled during preprocessing)

### Feature Categories:

* **Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item, Category, Amount, Season
* **Behavior:** Discounts, Frequency, Ratings, Shipping Type

---

## ⚙️ Tech Stack

* SQL
* Python
* Microsoft Power BI

---

## 🔄 Project Workflow

### 1. Data Extraction & Cleaning (SQL + Python)

* Cleaned and structured raw data using SQL queries
* Handled missing values (imputed ratings using category medians)
* Removed redundant columns and standardized naming conventions

### 2. Data Analysis (Python)

* Performed Exploratory Data Analysis (EDA) using pandas
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Identified behavioral and transactional patterns

### 3. Data Visualization (Power BI)

* Built an interactive dashboard with:

  * KPIs (Revenue, Avg Purchase, Ratings)
  * Customer segmentation
  * Sales trends
  * Category-level insights
* Enabled filtering by gender, subscription, category, and shipping

---

## 📊 Key Insights

* 💰 **Revenue Concentration:** A small segment of customers contributes disproportionately to total revenue
* 🚚 **High-Value Segment:** Express shipping users spend more on average
* 📉 **Subscription Gap:** ~73% customers are non-subscribers → major conversion opportunity
* 🔁 **Customer Loyalty:** Majority of repeat buyers are not subscribed
* 🛍️ **Top Products:** Items like Gloves, Sandals, and Boots have the highest ratings
* 🎯 **Discount Dependency:** Certain products rely heavily on discounts to drive sales
* 👥 **Demographic Trends:** Young adults contribute the highest revenue

---

## 💡 Business Recommendations

* 🚀 **Increase Subscriptions:** Target non-subscribers with personalized offers
* 🎁 **Loyalty Programs:** Reward repeat customers to boost retention
* ⚖️ **Optimize Discounts:** Balance between sales growth and profitability
* 📢 **Targeted Marketing:** Focus on high-value segments (young adults, express users)

---


<img width="1225" height="726" alt="DashBoard" src="https://github.com/user-attachments/assets/d5939470-dd5c-403a-992b-f28f3beb8a6f" />


---



## 📈 Outcome

* Built a complete **data analytics pipeline (SQL → Python → Power BI)**
* Generated actionable insights from raw data
* Demonstrated ability to connect technical analysis with business decisions

---

