# Retail Sales Performance & KPI Dashboard (Power BI)

##  Project Overview
This project focuses on transforming raw retail transaction data into a **Sales Performance and KPI Dashboard** that supports data‑driven business decisions.

The goal is to help retail stakeholders quickly understand:
- Revenue performance
- Customer behavior
- Product and category trends
- Sales growth over time

---

## Dataset Description
The dataset contains **100,000+ retail transactions** covering the period 2024–2025.

### Key data fields include:
- **Transaction data:** transaction_id, transaction_date
- **Customer data:** customer_id, customer_gender, customer_age_group, customer_segment
- **Product data:** product_id, product_name, category, brand
- **Sales metrics:** quantity, unit_price, discount_pct, sales_amount
- **Business attributes:** payment_method, sales_channel, region

Each row represents a single completed sales transaction.

---

## Project Objectives
- Track overall **sales revenue and performance**
- Identify **top‑performing products and categories**
- Analyze **customer segments** (New, Returning, Loyal, VIP)
- Compare sales across **regions and channels**
- Identify **monthly and yearly sales trends**

---

##  Data Cleaning & Preparation
Before analysis, the raw dataset was cleaned to ensure accuracy and consistency:

- Converted `transaction_date` to datetime format
- Ensured numeric fields were stored correctly
- Removed duplicate transactions
- Handled missing and invalid values
- Created time‑based features (year, month)

Raw data is preserved in `data/raw`, and cleaned data is saved to `data/cleaned`.

---

##  Dashboard & Analysis
The cleaned dataset is used to build an interactive **Power BI dashboard** that includes:

- Total Sales, Orders, and Average Order Value
- Monthly Sales Trends
- Sales by Product Category
- Sales by Region and Channel
- Customer Segment Performance
- Top Products by Revenue

The dashboard is designed for **executive and operational reporting**, with filters and drill‑downs for deeper analysis.

---

##  Key Insights
- A small number of categories contribute the majority of revenue
- VIP and Loyal customers generate higher average order values
- Sales channel performance varies by region
- Discounting increases sales volume but impacts profitability
- Sales trends show clear seasonal and regional patterns

---

## Tools & Technologies
- **Python (Pandas)** – data cleaning and preparation
- **Power BI** – data modeling and dashboard development
- **Jupyter Notebook** – documenting the cleaning process

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

## ✅ Outcome
This project demonstrates a professional end‑to‑end workflow:
from raw data → clean dataset → KPI dashboard,
delivering insights that support smarter retail business decisions.