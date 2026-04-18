#  Superstore Sales Analysis | End-to-End Data Analytics Project

##  Project Overview

This project performs an **end-to-end data analysis** on the Superstore dataset to extract meaningful business insights related to **sales, profit, customers, and regional performance**.

It demonstrates a real-world data workflow by combining:

*  **Python (Pandas)** for data cleaning & EDA
*  **SQL** for business-driven analysis

---

##  Objectives

* Identify **top-performing categories and products**
* Detect **loss-making areas**
* Analyze **customer and regional performance**
* Understand the **impact of discounts on profit**
* Track **sales and profit trends over time**

---

##  Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* SQL (MySQL)
* Excel

---

##  Project Workflow

### 1️ Data Cleaning & Feature Engineering (Python)

* Handled missing values
* Converted date columns
* Created new features:

  * `order_year`
  * `order_month`
  * `shipping_days`

### 2️ Exploratory Data Analysis (EDA)

* Analyzed sales and profit distributions
* Identified trends, patterns, and anomalies

### 3️ Data Export

```python
df.to_excel("cleaned_superstore.xlsx", index=False)
```

### 4️ SQL Analysis

* Imported cleaned dataset into SQL
* Performed business queries to derive insights

---

##  Project Structure

```
Superstore-End-to-End-Project/
│
├── README.md
├── data/
│   └── superstore.csv
├── 1_EDA/
│   ├── Superstorer_EDA.ipynb
│   └── README.md
├── 2_SUPERSTORE_SQL_ANALYSIS/
│   └── superstore_analysis.sql
|   └── README.md
|── images
```

---

##  Key Business Questions & Insights

###  Category & Product Analysis

* Technology category generates the **highest profit**
* Some sub-categories (e.g., tables/bookcases) consistently show **low or negative profit**
* Certain products are **always loss-making**

---

###  Discount Impact

* High discounts (>20–30%) significantly **reduce profit**
* Many loss-making orders are linked to **heavy discounting**

---

###  Regional & State Analysis

* Some regions generate **high sales but low profit**
* Certain states dominate overall profit contribution
* Indicates **operational inefficiencies in specific regions**

---

###  Customer Analysis

* A small group of customers contributes **majority of total profit**
* These customers are critical for **business retention strategies**

---

###  Time-Based Analysis

* Sales show **seasonal trends**
* High sales periods do not always result in high profit
* Year-over-year growth shows **overall business expansion**

---

###  Profitability Analysis

* Profit margin varies significantly across sub-categories
* Some segments generate revenue but **fail to generate profit**

---

##  Key Findings

*  High discounts are the **primary cause of losses**
*  Sales ≠ Profit → high revenue doesn’t guarantee profitability
*  Several sub-categories and products consistently generate losses
*  Regional performance is uneven, indicating inefficiencies
*  A few customers drive a large share of profit
*  Sales and profit follow seasonal patterns

---

##  Sample Visualizations (Add Screenshots Here)

* Sales vs Profit trend
* Discount vs Profit scatter plot
* Region-wise profit comparison

---

##  Future Improvements

* Build interactive dashboards (Power BI / Tableau)
* Perform advanced customer segmentation
* Apply machine learning for profit prediction

---

##  Resume Value

This project demonstrates:

* ✔ End-to-end data analysis pipeline
* ✔ Strong SQL and Python skills
* ✔ Business-oriented problem solving
* ✔ Real-world dataset handling

---

##  Author

**Aditya Jadhav**

*  GitHub: https://github.com/adityajadhav28
*  LinkedIn: https://www.linkedin.com/in/aditya-jadhav-4a1376258/

---

⭐ If you found this project useful, consider giving it a star!

