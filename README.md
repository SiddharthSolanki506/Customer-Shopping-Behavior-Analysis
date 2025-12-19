
# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into purchasing patterns, customer segments, product preferences, and subscription behavior. The objective is to help businesses make **data-driven decisions** to improve sales, customer engagement, and long-term loyalty.

The analysis combines **Python (EDA & data cleaning)**, **SQL (business queries)**, and **Power BI (interactive dashboard)** to deliver end-to-end analytics insights .

---

## 🎯 Business Problem

A retail company wants to understand how factors like **demographics, discounts, shipping type, reviews, and subscriptions** influence customer purchasing decisions.

**Key Question:**

> How can customer shopping data be leveraged to identify trends, improve engagement, and optimize marketing and product strategies? 

---

## 📊 Dataset Details

* **Total Records:** 3,900 purchases
* **Total Columns:** 18
* **Key Features:**

  * Customer Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item, Category, Amount, Season
  * Behavior Metrics: Discounts, Reviews, Shipping Type, Purchase Frequency
* **Missing Values:** 37 (only in Review Rating column) 

---

## 🧹 Data Preparation (Python)

* Loaded dataset using **Pandas**
* Performed initial exploration using `.info()` and `.describe()`
* Handled missing values by imputing median review ratings
* Standardized column names (snake_case)
* Feature engineering:

  * Age groups
  * Purchase frequency
* Integrated cleaned data with **PostgreSQL** for SQL analysis 

---

## 🗄️ SQL Analysis (PostgreSQL)

Key business insights extracted using SQL:

* Revenue comparison by gender
* High-spending customers who still use discounts
* Top-rated products by average review rating
* Standard vs Express shipping spend comparison
* Subscriber vs non-subscriber revenue analysis
* Customer segmentation: New, Returning, Loyal
* Revenue contribution by age group 

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** was built to visualize:

* Total customers & average purchase value
* Revenue by category and age group
* Subscription impact on revenue
* Shipping preference impact on spending
* Customer segmentation overview 

---

## 💡 Key Insights

* Express shipping users spend more per transaction
* Subscribers contribute a significant share of revenue
* Loyal customers form the most valuable segment
* Certain products are highly discount-dependent
* Middle-aged and young adults drive maximum revenue 

---

## 📂 Repository Structure

```
📁 Customer-Shopping-Behavior-Analysis
│── 📄 Customer_Shopping_Behavior_Analysis.ipynb
│── 📄 customer_behavior_sql_queries.sql
│── 📄 customer_behavior_dashboard.pbix
│── 📄 customer_shopping_behavior.csv
│── 📄 Customer Shopping Behavior Analysis.pdf
│── 📄 Business Problem Document.pdf
│── 📄 Customer-Shopping-Behavior-Analysis.pptx
│── 📄 README.md
```


## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL:** PostgreSQL
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook, VS Code

---

## 🚀 Business Recommendations

* Promote subscriptions with exclusive benefits
* Introduce loyalty programs for repeat buyers
* Optimize discount strategies for high-value products
* Focus marketing on high-revenue age groups
* Highlight top-rated products in campaigns 

---
