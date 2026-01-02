# Customer Shopping Analysis 🛒📊

Analyze customer shopping behavior to uncover spending trends, product performance, and loyalty patterns using Python, SQL, and Power BI.


## 📁 Project Overview

A retail company wants to understand **what drives customer purchases** so they can boost sales and improve loyalty programs.

This project analyzes **3,900 customer transactions (18 features)** to answer:

- Who are the most valuable customers?
- Which products and categories drive revenue?
- How do discounts, subscriptions, and shipping type affect spend?
- Which segments should the business target for marketing and promotions?


## 📊 Dataset Summary

- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**
  - **Demographics:** `age`, `gender`, `location`, `subscription_status`
  - **Purchase Info:** `item_purchased`, `category`, `purchase_amount`, `season`, `size`, `color`
  - **Behavior:** `discount_applied`, `promo_code_used`, `previous_purchases`, `frequency`, `review_rating`, `shipping_type`
- **Missing Values:** 37 missing entries in `review_rating` (handled in preprocessing)


## 🧰 Tech Stack

- **Language:** Python (pandas, numpy, matplotlib, sqlalchemy/psycopg2)
- **Database:** PostgreSQL (SQL analysis)
- **BI Tool:** Power BI (interactive dashboard)


## 🗂 Repository Structure

```bash
.
├── customer_shopping_data.csv          # Raw dataset
├── customer_shopping_analysis.ipynb    # Python EDA & preprocessing
├── customer_shopping_analysis.sql      # SQL queries for business questions
├── customer_shopping_analysis.pbix     # Power BI dashboard
└── README.md                           # Project documentation
