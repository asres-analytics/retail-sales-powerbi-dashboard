# Retail Sales Performance & KPI Dashboard (Power BI)

## 📌 Project Overview
This project focuses on cleaning, preparing, and analyzing retail sales transaction data to build a **Sales Performance and KPI Dashboard** using Power BI.

The objective is to transform raw transactional data into meaningful insights that help businesses understand revenue trends, customer behavior, and overall sales performance.

---

## 📊 Dataset Description
The dataset contains **120,000 retail transactions** covering sales activities across multiple regions, product categories, and sales channels.

### Key fields include:
- **Transaction data:** transaction_id, transaction_date
- **Customer data:** customer_id, customer_gender, customer_age_group, customer_segment
- **Product data:** product_id, product_name, category, brand
- **Sales metrics:** quantity, unit_price, discount_pct, sales_amount
- **Business attributes:** payment_method, sales_channel, region

Each row represents a single completed sales transaction.

---

## 🎯 Project Objectives
- Analyze overall **sales revenue and performance**
- Identify **top-performing products and categories**
- Understand **customer segments** and purchasing behavior
- Compare performance across **regions and sales channels**
- Analyze **monthly and yearly sales trends**

---

## 🧹 Data Cleaning & Preparation
Before analysis, the dataset was thoroughly cleaned and prepared using Python (Pandas):

- Verified that there are **no missing values**
- Converted `transaction_date` to datetime format
- Ensured numeric columns have correct data types
- Created time‑based features (year, month, year_month)
- Preserved raw data and exported a cleaned dataset

Raw data is stored in `data/raw`, and the final cleaned dataset is stored in `data/cleaned`.

---

## 📈 Dashboard Development (Power BI)
The cleaned dataset is used to develop a Power BI dashboard featuring:

- Total Sales, Total Orders, and Average Order Value (AOV)
- Monthly and yearly sales trends
- Sales by product category and region
- Sales channel comparison (Online, In‑Store, Mobile App)
- Customer segment performance
- Top products by revenue

The dashboard is designed for **business users and decision‑makers**, with interactive filters and clear KPI indicators.

---

## 💡 Key Insights (Examples)
- A small number of categories contribute a large share of total revenue
- VIP and Loyal customers generate higher average order values
- Online sales outperform in‑store sales in several regions
- Sales performance varies significantly by month and region

---

## 🛠 Tools & Technologies
- **Python (Pandas)** – data cleaning and preparation
- **Jupyter Notebook** – documentation of the cleaning process
- **Power BI** – data modeling and dashboard creation

---


## 📂 Project Structure

retail-sales-powerbi-dashboard/

├── data/

│   ├── raw/

│   │   └── retail_sales_dataset.csv

│   └── cleaned/

│       └── retail_sales_cleaned.csv

├── notebooks/

│   └── data_cleaning.ipynb

├── powerbi/

│   └── sales_kpi_dashboard.pbix

├── screenshots/

│   └── dashboard_preview.png

└── README.md


---

---

## ✅ Project Status
- ✔ Raw data added and preserved
- ✔ Data cleaning completed and documented
- ✔ Cleaned dataset prepared for Power BI
- ⏳ Power BI dashboard under development
---

## ✅ Outcome
This project demonstrates a professional end‑to‑end workflow:
from raw data → clean dataset → KPI dashboard,
delivering insights that support smarter retail business decisions.