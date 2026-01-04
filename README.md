# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project is a **complete end-to-end Data Analytics portfolio project** that analyzes **Customer Shopping Trends from Retail Transaction Data** using **SQL, Python, and Power BI**.

The goal is to transform raw retail data into **actionable business insights** that help organizations improve revenue, customer retention, and marketing strategies.

This project follows **industry-standard data analytics workflow** and is suitable for **Data Analyst / Business Intelligence roles**.

---

## 🎯 Business Problem

Retail businesses generate large volumes of transactional data, but without structured analysis, it is difficult to:

* Understand customer purchasing behavior
* Identify high-value customers
* Measure the impact of discounts, shipping modes, and subscriptions
* Improve customer retention and revenue growth

This project addresses these challenges by performing **data-driven analysis** on customer shopping behavior.

---

## 🧠 Objectives

* Analyze customer demographics and purchase behavior
* Identify high-revenue customer segments
* Evaluate impact of discounts, shipping methods, and subscriptions
* Discover top-performing products
* Provide business-ready insights using dashboards and SQL queries

---

## 📊 Dataset Overview

* **Total Records:** 3,900 purchases
* **Total Columns:** 18
* **Data Type:** Retail transaction data
* **Missing Values:** 37 (only in `Review Rating` column)

### Key Columns

* Customer ID
* Gender
* Age
* Item Purchased
* Category
* Purchase Amount
* Discount Applied
* Shipping Type
* Subscription Status
* Review Rating
* Payment Method

---

## 🧹 Data Preparation & Cleaning (Python)

Performed using **Pandas & NumPy**:

* Loaded dataset and checked structure
* Handled missing values (median imputation for Review Rating)
* Verified data types and value ranges
* Feature engineering:

  * Created **Age Groups**
  * Calculated **Purchase Frequency**

---

## 🗄️ SQL Analysis (PostgreSQL)

The cleaned dataset was loaded into **PostgreSQL** for structured querying.

### Key SQL Analyses

* Revenue by gender
* Top-rated products
* Average purchase value by shipping type
* Subscription vs non-subscription revenue
* High-value discount users
* Customer segmentation (New, Returning, Loyal)

📌 *SQL was used to simulate real-world data warehouse analysis scenarios.*

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize insights:

### Dashboard Highlights

* Revenue by gender
* Subscription impact on spending
* Shipping preference vs purchase amount
* Customer segmentation overview
* Top-rated products

The dashboard enables **business users to explore insights visually** and supports data-driven decision-making.

---

## 🔍 Key Insights

* Female customers generate slightly higher revenue than male customers
* Express shipping customers spend **~12% more per transaction**
* Subscription customers contribute:

  * **45% of total revenue**
  * **68% higher average spend**
  * **78% repeat purchase rate**
* High-value customers often use discounts strategically
* Products like **Blouse, Dress, and Shirt** receive the highest ratings

---

## 🧩 Customer Segmentation

Customers were segmented into:

| Segment   | Percentage | Description                |
| --------- | ---------- | -------------------------- |
| New       | 50%        | First-time buyers          |
| Returning | 35%        | Repeat customers           |
| Loyal     | 15%        | High-value frequent buyers |

🎯 *Business focus should be on converting New → Returning → Loyal customers.*

---

## 💡 Strategic Recommendations

* Promote subscriptions with exclusive benefits
* Introduce loyalty programs for repeat buyers
* Target express shipping users with premium offers
* Highlight top-rated products in marketing campaigns
* Design discount strategies for high-value customers

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy)
* **SQL** (PostgreSQL)
* **Power BI** (Data visualization & dashboards)
* **Excel / CSV** (Data source)

---

## 📁 Repository Structure

```
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Shopping_Analysis.ipynb
├── sql/
│   └── customer_analysis_queries.sql
├── dashboard/
│   └── Customer_Shopping_Dashboard.pbix
├── Customer-Shopping-Behavior-Analysis.pptx
├── README.md
```

---

## ✅ Conclusion

This project demonstrates strong **data analytics fundamentals**, real-world business thinking, and hands-on experience with **SQL, Python, and Power BI**. It is well-suited for showcasing skills in **Data Analyst, Business Analyst, and BI roles**.

---

