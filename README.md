# 🛍️ **CUSTOMER SHOPPING BEHAVIOR ANALYSIS**

### A data analytics project that explores customer purchasing patterns, product preferences, and subscription behavior using **Python, SQL, and Power BI** to generate actionable business insights.

---

## 📌 Project Overview

This project analyzes **3,900 customer transactions** across multiple product categories to:

* Understand spending behavior
* Segment customers based on purchase history
* Identify top-performing products
* Evaluate the impact of discounts and subscriptions
* Support data-driven business decisions

---

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18

### Key Features

* **Demographics** → Age, Gender, Location, Subscription Status

* **Purchase Details** → Item, Category, Amount, Season, Size, Color

* **Behavior Metrics** → Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type

* **Missing Values:** 37 in `review_rating` (handled using median by category)

---

## 🛠️ Tech Stack

* **Python** → Pandas, Data Cleaning, Feature Engineering
* **PostgreSQL** → Business queries & segmentation
* **Power BI** → Interactive dashboard & KPI visualization

---

## ⚙️ Data Preprocessing

* Handled missing values using **median imputation by product category**
* Standardized column names to **snake_case**
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant column: `promo_code_used`
* Loaded cleaned data into **PostgreSQL** for SQL analysis

---

## 🧠 Business Questions Answered (SQL)

* Revenue by gender
* High-spending customers who still used discounts
* Top 5 highest-rated products
* Average purchase: Standard vs Express shipping
* Subscribers vs Non-subscribers (revenue & spend)
* Discount-dependent products
* Customer segmentation → New, Returning, Loyal
* Top 3 products per category
* Repeat buyers vs subscription likelihood
* Revenue contribution by age group

---

## 📈 Key Insights

* Loyal customers form the **largest segment**
* Express shipping users **spend more on average**
* Discounts **do not always reduce revenue**
* Some products are **highly discount-driven**
* **Young adults** generate the highest revenue share

---

## 📊 Power BI Dashboard

The interactive dashboard includes:

* KPI Cards → Total Customers, Avg Purchase Amount, Avg Rating
* Revenue by Category
* Subscription filter
* Shipping type filter
* Customer distribution by subscription status

🎨 Dark-themed UI with neon highlights for better visual storytelling.

---

## 🧩 Customer Segmentation

Customers were classified into:

* **New** → First-time buyers
* **Returning** → Multiple purchases
* **Loyal** → High purchase frequency

This enables **targeted marketing and retention strategies**.

---

## 💡 Business Recommendations

* Introduce **subscription-exclusive benefits**
* Launch **loyalty programs** for repeat buyers
* Optimize **discount strategy** to protect margins
* Promote **top-rated and best-selling products**
* Target **high-revenue age groups** with personalized campaigns

---

## 🚀 Project Structure

```
customer-shopping-analysis/
│── data/
│── notebooks/
│── sql/
│── powerbi/
│── dashboard_screenshots/
│── README.md
```

---

## ▶️ How to Run

### 1️⃣ Python (Data Cleaning)

```bash
pip install pandas numpy sqlalchemy psycopg2
```

### 2️⃣ Load Clean Data into PostgreSQL

* Update DB credentials
* Run the ETL script

### 3️⃣ Execute SQL Queries

Run queries from `/sql` folder for business insights.

### 4️⃣ Open Power BI Dashboard

Load the processed dataset to view interactive visuals.

---

## 📌 Use Cases

* Retail analytics
* Customer segmentation
* Revenue optimization
* Marketing strategy planning

---

## 👩‍💻 Author

**Pragati Mishra**
Full Stack Developer | Data Analytics Enthusiast
**Tech:** MERN | Python | SQL | Power BI | AI/ML
