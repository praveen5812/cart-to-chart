# 🛒 Cart to Chart — Customer Behavior Analysis

A complete end-to-end data analysis project analyzing customer shopping behavior across **3,900 customers** using Python, SQL Server, and Power BI.

---

## 📊 Dashboard Preview

![Customer Behavior Dashboard](<img width="1346" height="741" alt="image" src="https://github.com/user-attachments/assets/dd83eb49-7e4a-45de-aeaa-9f20d7b0f6ba" />
)

---

## 📁 Project Structure

```
cart-to-chart/
│
├── data/
│   ├── customer_raw.csv              ← Original dataset
│   └── customer_cleaned.csv          ← Cleaned dataset after Python processing
│
├── customer_analysis.ipynb           ← Python analysis (Google Colab)
├── customer_queries.sql              ← SQL Server queries
├── customer_dashboard.pbix           ← Power BI dashboard
└── README.md                         ← Project documentation
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python (Google Colab) | Data cleaning and exploration |
| SQL Server | Data analysis and querying |
| Power BI | Dashboard and visualization |

---

## 📌 Dataset Overview

| Column | Description |
|---|---|
| customer_id | Unique customer identifier |
| age / age_group | Customer age and age category |
| gender | Male / Female |
| item_purchased | Product name |
| category | Clothing, Accessories, Footwear, Outerwear |
| purchase_amount_usd | Transaction value in USD |
| season | Spring, Summer, Fall, Winter |
| review_rating | Customer rating (1–5) |
| subscription_status | Yes / No |
| shipping_type | Express, Standard, Free Shipping, etc. |
| payment_method | Venmo, PayPal, Credit Card, etc. |
| previous_purchases | Number of past purchases |

---

## 🐍 Python — Data Cleaning (Google Colab)

- Imported dataset using Pandas
- Explored data with `df.head()`, `df.info()`, `df.describe()`
- Checked and handled missing values
- Cleaned and prepared data for SQL and Power BI analysis

---

## 🗄️ SQL Server — Key Queries

| # | Query |
|---|---|
| Q1 | Total revenue by gender |
| Q2 | Discount customers who spent above average |
| Q3 | Top 5 products by average review rating |
| Q4 | Average purchase by shipping type |
| Q5 | Subscriber vs non-subscriber spending |
| Q6 | Top 5 products by discount rate |
| Q7 | Customer segmentation — New, Returning, Loyal |
| Q8 | Top 3 products per category |
| Q9 | Repeat buyers and subscription likelihood |
| Q10 | Revenue contribution by age group |

---

## 📈 Power BI Dashboard

The dashboard includes:

- **KPI Cards** — Total Customers, Average Purchase, Average Review Rating, Total Revenue
- **Subscription Status** — Donut chart (Yes 27% / No 73%)
- **Revenue by Category** — Clothing leads at $104K
- **Revenue by Gender** — Male customers generate more revenue
- **Top 5 Items Purchased** — Blouse, Jewelry, Pants, Shirt, Dress
- **Revenue by Age Group** — Young Adults drive the most revenue
- **Seasonal Trends** — Fall is the peak season at $60K

### 🔍 Key Insights

- 🏆 **Fall** is the best performing season ($60K revenue)
- ☀️ **Summer** is the weakest season ($55.8K revenue)
- 👕 **Clothing** is the top category ($104K)
- 👨 **Male** customers generate more revenue than female
- 🧑 **Young Adults** contribute the highest revenue by age group
- 📦 Only **27%** of customers are subscribers — room for growth

---

## 🚀 How to Use This Project

1. Open `customer_analysis.ipynb` in Google Colab for Python analysis
2. Run `customer_queries.sql` in SQL Server Management Studio
3. Open `customer_dashboard.pbix` in Power BI Desktop

---

## 👤 Author

**Praveen**  
Aspiring Data Analyst  
www.linkedin.com/in/praveen-singh-285652326
https://github.com/praveen5812
