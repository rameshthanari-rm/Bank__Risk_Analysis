# 📘 Project Documentation  
### **Banking Risk Analysis – End-to-End Data Analytics Project**  
_By Ramesh Thanari_

---

## 📝 Table of Contents

1. [Project Overview](#1-project-overview)  
2. [Tools & Technologies Used](#2-tools--technologies-used)  
3. [Project Architecture](#3-project-architecture)  
4. [Data Source & Description](#4-data-source--description)  
5. [Process Workflow](#5-process-workflow)  
6. [Exploratory Data Analysis (EDA)](#6-exploratory-data-analysis-eda)  
7. [Power BI Dashboard](#7-power-bi-dashboard)  
8. [Key Findings](#8-key-findings)  
9. [Conclusion](#9-conclusion)  
10. [Author & Contact](#10-author--contact)

---

## 1. 📌 Project Overview

The **Banking Risk Analysis** project aims to identify, assess, and visualize the risk associated with banking customers based on their credit score, loan type, age group, and financial activity. This end-to-end data analysis project showcases how to move from raw data to meaningful business insights using various data tools and techniques.

---

## 2. 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Excel** | Initial data entry and formatting |
| **MySQL** | Data storage and querying |
| **Jupyter Notebook (Python)** | EDA and data visualization |
| **Power BI** | Dashboard creation and visual storytelling |
| **Pandas, NumPy** | Data manipulation |
| **Matplotlib, Seaborn** | EDA visualization |
| **DAX** | Power BI measures and KPIs |
| **Power Query** | Data shaping in Power BI |

---

## 3. 🗂️ Project Architecture

```
Excel (Raw Data) 
     ↓
MySQL Database 
     ↓
Jupyter Notebook (EDA)
     ↓
Power BI Dashboard
```

---

## 4. 📄 Data Source & Description

- The dataset was manually created in Excel and uploaded into MySQL for structured storage.
- Data includes:
  - Customer ID, Age, Gender, Loan Type
  - Credit Score, Balance, Loan Status
  - Location and Account Type

---

## 5. 🔄 Process Workflow

### Step 1: Data Collection
- Created and formatted Excel sheet with customer financial and demographic data

### Step 2: Data Upload
- Imported Excel file into MySQL using SQL queries

### Step 3: Exploratory Data Analysis (EDA)
- Loaded MySQL data into Jupyter using `mysql.connector` and `SQLAlchemy`
- Cleaned nulls, standardized formats, removed duplicates
- Explored variable distributions, correlations, and class imbalance

### Step 4: Dashboard Development
- Imported cleaned data into Power BI
- Created:
  - Cards for KPIs
  - Bar charts, Pie charts, Tree maps
  - Slicers for filters (Loan Type, Age Group, Credit Score)

---

## 6. 🔍 Exploratory Data Analysis (EDA)

Performed using `EDA.ipynb`. Covered:

- Descriptive statistics (mean, median, mode)
- Null value analysis
- Outlier detection (IQR method)
- Risk segmentation based on credit score and age
- Visualizations: histograms, boxplots, correlation heatmaps

---

## 7. 📊 Power BI Dashboard

**Key visuals included:**

- 🧮 **KPI Cards**: Total Loans, Avg Credit Score, Total Customers  
- 📈 **Loan Type Distribution**  
- 📊 **Risk Segmentation by Credit Score**  
- 🧓 **Customer Age Group Trends**  
- 🗂️ **Balance & Credit Score Trends**  
- 🔘 **Dynamic Filters**: Loan Type, Location, Risk Class

---

## 8. 🔑 Key Findings

- Majority of high-risk customers belong to the 30–40 age group
- Customers with low credit scores also show low average balances
- Auto and personal loans have a higher default rate compared to others
- Regional variation in risk profile is noticeable

---

## 9. ✅ Conclusion

This project showcases how raw customer data can be transformed into actionable insights using a structured analytics pipeline. By combining SQL, Python, and Power BI, the risk profile of banking customers was effectively identified and visualized.

---

## 10. 👨‍💻 Author & Contact

**Ramesh Thanari**  
📧 Email: rameshthanari9542@gmail.com 
🔗 LinkedIn: www.linkedin.com/in/ramesh-thanari


---
