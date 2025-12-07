 📊 **Customer Behavior Analysis – End-to-End Data Analytics Project**

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server-orange)
![Power BI](https://img.shields.io/badge/PowerBI-Interactive%20Dashboard-yellow)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📘 **Table of Contents**

* [Overview](#overview)
* [Dataset](#dataset)
* [Tools & Technologies](#tools--technologies)
* [Project Architecture](#project-architecture)
* [Workflow](#workflow)
* [Power BI Dashboard](#power-bi-dashboard)
* [Key Insights](#key-insights)
* [How to Run](#how-to-run)
* [Project Files](#project-files)
* [Contact](#contact)

---

## 📌 **Overview**

This project demonstrates a complete **end-to-end data analytics pipeline**, starting from loading raw customer shopping data in Python, performing EDA and data cleaning, running business queries in SQL, and visualizing insights using **Power BI**.

The project also includes a **final report (PDF)** and a **Gamma.app presentation**, making it portfolio-ready for data analyst / business intelligence roles.

---

## 📂 **Dataset**

* **3,900+ customer transactions**
* **18 columns** including:

  * Age, Gender, Location
  * Item purchased & Category
  * Purchase Amount
  * Discount & Promo usage
  * Shipping type
  * Review rating
  * Subscription status
* Contains missing values handled during cleaning

---

## 🛠️ **Tools & Technologies**

| Step                | Tools                             |
| ------------------- | --------------------------------- |
| Data Cleaning & EDA | Python, Pandas, NumPy, Matplotlib |
| Database Analysis   | PostgreSQL / MySQL / SQL Server   |
| Visualization       | Power BI                          |
| Documentation       | MS Word / PDF                     |
| Presentation        | Gamma.app                         |
| Version Control     | Git & GitHub                      |

---

## 🧱 **Project Architecture**

```
customer_behaviour_analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── shopping_behaviour_updated.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── customers_behavior_dashboard.pbix
│
├── reports/
│   ├── customers_shopping_behavior_analysis.pdf
│   └── presentation_gamma.pdf (optional)
│
└── README.md
```

---

## 🚀 **Workflow**

### **1️⃣ Data Loading (Python)**

* Imported raw CSV data using Pandas
* Inspected structure using `.info()`, `.describe()`
* Checked missing values, inconsistencies, and duplicates

---

### **2️⃣ Exploratory Data Analysis (EDA)**

Performed visual and statistical analysis:

* Distribution of age, spending patterns
* Category-wise sales
* Relationship between discounts & revenue
* Review rating distribution
* Customer subscription behavior

---

### **3️⃣ Data Cleaning & Feature Engineering**

* Handled missing values (e.g., Review Rating)
* Standardized column names
* Dropped redundant fields
* Created:

  * `age_group`
  * `purchase_frequency_days`
* Exported cleaned dataset into SQL database

---

### **4️⃣ SQL Analysis**

Executed analytical SQL queries to answer business questions:

* Revenue by gender
* Top 5 rated products
* High-spending discount users
* Subscription vs non-subscription revenue
* Customer segmentation (New / Returning / Loyal)
* Product category leaders
* Revenue by age group
* Repeat buyers analysis

---

### **5️⃣ Power BI Dashboard**

An interactive dashboard was built to visually summarize:

* Total number of customers
* Average purchase amount
* Average review rating
* Revenue by category
* Sales by age group
* Subscription vs non-subscription split
* Shipping type comparison

---

## 📈 **Dashboard Preview**


![Dashboard](https://raw.githubusercontent.com/pranavkumarreddy69/customer_behaviour_analysis/main/dashboard.png.png)




## 🔍 **Key Insights**

* Young adults generate the highest revenue
* Express shipping customers spend more
* Subscription customers show different buying patterns
* Accessories & Clothing categories dominate revenue
* Discounts do not always increase total spending
* Loyal customers create long-term value

These insights can help businesses optimize pricing, marketing, and retention strategies.

---

## ▶️ **How to Run**

### **Clone the repository**

```bash
git clone https://github.com/pranavkumarreddy69/customer_behaviour_analysis.git
```

### **Install Python dependencies**

```bash
pip install -r requirements.txt
```

### **Run Jupyter Notebook**

```bash
jupyter notebook
```

### **Execute SQL Queries**

Import the `customer_behavior_sql_queries.sql` file into your SQL database (PostgreSQL/MySQL/SQL Server).

### **Open Power BI Dashboard**

Open the `.pbix` file using **Power BI Desktop**.

---

## 📄 **Project Files**

| File        | Description                 |
| ----------- | --------------------------- |
| `.ipynb`    | Data loading, cleaning, EDA |
| `.sql`      | All SQL business queries    |
| `.pbix`     | Power BI dashboard          |
| `.csv`      | Original dataset            |
| `.pdf`      | Final report                |
| `README.md` | Documentation               |

---


