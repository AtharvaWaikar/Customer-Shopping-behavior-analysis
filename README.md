# 🛍️ Customer Shopping Behavior Analysis

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,100:2563EB&height=220&section=header&text=Customer%20Shopping%20Behavior%20Analysis&fontSize=40&fontColor=ffffff&animation=fadeIn)

---

## 🏷️ Project Badges

![Python](https://img.shields.io/badge/Python-Data%20Processing-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-orange?logo=mysql)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Analysis-blue?logo=numpy)
![VS Code](https://img.shields.io/badge/IDE-VSCode-blue?logo=visualstudiocode)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📊 Project Overview

This project analyzes **customer shopping behavior using a complete data analytics pipeline**.

The objective is to understand **customer demographics, purchasing trends, subscription behavior, product preferences, and revenue patterns** to generate actionable business insights.

The project processes **3,900 transaction records** and converts raw retail data into meaningful insights through **data cleaning, SQL analysis, and interactive visualization**.

---

# ⚙️ Project Architecture

```
Dataset
   │
   ▼
Python (Data Cleaning & Feature Engineering)
   │
   ▼
MySQL Workbench (SQL Analysis)
   │
   ▼
Power BI (Interactive Dashboard)
```

---

# 🧹 Data Cleaning & Processing (Python)

Performed preprocessing using **Python, Pandas, and NumPy**.

### Key Tasks

- Dataset exploration using `info()` and `describe()`
- Handling missing values
- Column renaming and formatting
- Data standardization
- Feature engineering
- Age group creation
- Purchase frequency calculations
- Removing redundant columns
- Exporting clean dataset for SQL analysis

---

# 🗄️ Database Analysis (MySQL)

The cleaned dataset was imported into **MySQL Workbench** to perform SQL-based business analysis.

### Key Queries

- Revenue by **gender**
- **Subscribers vs non-subscribers** spending
- **High spending discount users**
- **Top 5 products by rating**
- Shipping type impact on **purchase value**
- Customer segmentation:
  - New
  - Returning
  - Loyal
- **Top products per category**
- **Repeat buyers & subscription behavior**
- Revenue by **age group**

---

# 📊 Power BI Dashboard

An **interactive Power BI dashboard** was developed to visualize insights and support decision making.

### Dashboard Features

- KPI cards
- Sales distribution charts
- Category analysis
- Gender based purchase insights
- Subscription analysis
- Customer segmentation
- Interactive slicers
- Dynamic filtering

📌 Users can explore customer trends dynamically.

---

# 🔍 Key Insights

### 📈 Demographics & Revenue

Certain **age groups generate significantly higher revenue**, making them important marketing targets.

### ⭐ Product Performance

Top-rated products indicate strong **product-market fit and customer satisfaction**.

### 💳 Subscription Behavior

Subscribers generate **higher average spending and consistent revenue**.

### 🎯 Discount Strategy

A group of **high-spending discount users** exists, meaning discounts can increase purchases without reducing value.

### 🚚 Shipping Preference

Customers using **express shipping tend to spend more**, indicating premium buyer segments.

---

# 👥 Customer Segmentation

Customers were segmented into three groups:

| Segment | Description |
|------|------|
| New | First-time buyers |
| Returning | Customers with multiple purchases |
| Loyal | High-frequency long-term customers |

---

# 🛠️ Tech Stack

| Tool | Purpose |
|-----|------|
| Python | Data preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| MySQL Workbench | SQL querying |
| Power BI | Data visualization |
| VS Code | Development |

---

# 📂 Repository Structure

```
Customer-Shopping-Behavior-Analysis
│
├── dataset
│   └── shopping_data.csv
│
├── python
│   └── data_cleaning.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── powerbi
│   └── dashboard.pbix
│
└── README.md
```

---

# 📌 Business Recommendations

- Increase **subscription adoption**
- Launch **loyalty reward programs**
- Optimize **discount campaigns**
- Focus marketing on **high-revenue demographics**
- Promote **top-rated products**
- Upsell **express shipping services**

---

# 🚀 Future Improvements

- Real-time dashboard integration
- Customer churn prediction
- Recommendation systems
- Predictive sales analytics
- Machine learning customer segmentation

---

# 📖 Conclusion

This project demonstrates a **complete data analytics workflow** from **raw data processing to business intelligence visualization**.

The insights generated help businesses improve **customer retention, marketing strategies, and long-term revenue growth**.

---

# ⭐ If you found this project helpful, consider giving the repo a star!

---

# Atharva Waikar - Data Analyst

---

# 🔗 Connect With Me

LinkedIn: https://www.linkedin.com/in/atharva-waikar-a95a042b5/ \n
Portfolio: https://yourportfolio.com   \n
GitHub: https://github.com/AtharvaWaikar
