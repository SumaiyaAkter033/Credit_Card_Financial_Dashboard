# 💳 Credit Card Financial Dashboard
### A Complete End-to-End Power BI Project

---

## 📌 Project Objective
To develop a **Comprehensive Credit Card Weekly Dashboard** that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations efficiently.

---

## 📂 Deliverables
This project includes **two interconnected dashboards**:
- **Credit Card Transaction Report** – focuses on financial metrics, revenue sources, and transaction patterns.  
- **Credit Card Customer Report** – focuses on customer demographics, behavior, and segmentation.

---

## 🧮 Data Source & Workflow
Simulated a professional data pipeline using **SQL and Power BI**.

1. **Data Extraction (SQL):**
   - Loaded 4 CSV files — 2 main (credit_card_details, customer_details) and 2 supplementary (CC add, Customer add).
   - Created tables (`cc_details`, `cust_details`) in SQL and imported data using the `COPY` command.
   - Connected Power BI to SQL database (localhost) for real-time data import.

2. **Data Processing (Power BI):**
   - Cleaned and transformed data using **Power Query**.
   - Created calculated columns using **DAX**:
     - `Age Group` → categorized customers into age ranges (`SWITCH` function)
     - `Income Group` → classified into Low, Medium, High income brackets  
   - Built measures for key KPIs and week-over-week performance tracking.

---

## 📊 Dashboard Design
### **Dashboard 1: Credit Card Transaction Report**
- **KPI Cards** → Total Revenue, Interest, and Transactions.  
- **Stacked Column Charts** → Revenue by Expense Type, Education, and Job.  
- **Tree Map Slicers** → Interactive filters by Quarter, Gender, Card Type, Income Group.  
- **Data Table** → Revenue and Interest by Card Category.

### **Dashboard 2: Credit Card Customer Report**
- **Line Chart** → Weekly revenue trend by gender.  
- **KPI Cards** → Revenue, Income, Total Interest, Customer Satisfaction Score (CSS).  
- **Stacked Bar Charts** → Revenue by Age Group, Marital Status, and Top States.  
- **Slicers** → Week, Quarter, and Income Group.

---

## 📈 Key Insights
- **Total Revenue:** \$57M | **Total Income:** \$588M | **Total Interest:** \$46M  
- **Blue cardholders** generated the highest revenue (~\$47M).  
- **Q4** had the strongest quarterly performance (~\$14.5M).  
- **Bills, Entertainment, and Fuel** were top expenditure types.  
- **Businessmen** and **Self-employed** customers were the most profitable.  
- **High-income customers (aged 50–60)** were the top contributors.  
- **Swipe transactions** dominated over online and chip modes.

---

## 🧠 Skills & Tools Used
- **Power BI Desktop** – Data modeling, DAX, visualization  
- **SQL** – Data extraction and relational modeling  
- **Data Analysis Expressions (DAX)** – Calculated columns & measures  
- **Power Query** – Data cleaning and transformation  
- **Data Visualization & Storytelling**

---

## 🚀 Project Sharing
**GitHub Repository:** [Insert your repo link here]  
**LinkedIn Post:** [Insert LinkedIn post link here]

---

## Acknowledgment
**Guided by:** Rishabh Mishra  

---
