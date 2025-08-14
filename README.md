# Credit Card Financial Dashboard

## 📈 Project Overview
This repository presents a real-world **Credit Card Financial Dashboard** solution, integrating PostgreSQL (database management), Power BI (visual analytics), SQL scripting, dynamic CSV imports, and advanced DAX queries. The project quantitatively tracks customer and transaction data, enabling actionable financial insights for credit portfolios.

---

## 🎯 Key Highlights
- **End-to-End Data Pipeline:** Raw data (CSV) -- PostgreSQL (storage & manipulation) -- Power BI (business intelligence)
- **Interactive Analytics:** Explore multi-dimensional customer and transaction metrics, performance KPIs, trends, and operational patterns via vibrant Power BI dashboards.
- **Advanced Calculations:** Utilizes **DAX** (Data Analysis Expressions) inside Power BI for measures such as week-on-week (WoW) revenue change.
- **Business Relevance:** Features segmentation, product category analysis, acquisition costs, top states, and satisfaction scores—all derived from genuine, structured data.
- **Recruiter Focus:** Demonstrates professional-grade skills in SQL, DAX, BI tooling, database management, and dashboard storytelling.

---

## 📊 Features & Insights
- **Customer Segmentation:**  
  Age groups, gender, dependent count, education, income tiers, salary bands, state, marital status, job sector.
- **Card & Transaction Analytics:**  
  Card category (Platinum, Gold, Silver, Blue), annual fees, interest earned, revenue by expenditure type, transaction volumes, chip vs. swipe/online usage.
- **Dynamic CSV Data Integration:**  
  New weekly datasets (`cc_add.csv`, `cust_add.csv`) are appended to your data store and instantly reflected in dashboard views.
- **DAX-Based KPIs:**  
  Week-on-week revenue change, running totals, segment-wise performance, all with DAX measures for real BI scenarios.

---

## 🧑‍💻 Tech Stack
- **PostgreSQL:** Relational storage, SQL data import, schema management.
- **SQL:** Table creation, bulk data load with `COPY`, error management and troubleshooting date types.
- **Power BI:** Data modeling, dashboard design, cross-filtering, visualization storytelling.
- **DAX (Data Analysis Expressions):** Calculated columns, WoW change measures, switch logic for segmentation.
- **CSV Files:** Incremental weekly data import for real-time reporting.

---

## 🚀 Setup Instructions

#### 1. Database Initialization
- **Create Database:**
- **Run Table Creators** & import scripts (`SQL-Query-Financial-Dashboard-Data.sql`) for:
- `cc_detail`
- `cust_detail`
- **Import initial CSV:**
- **Handle Incremental Week Data:**

  *(See SQL file for error resolution tips for dates.)*

#### 2. Power BI Connection
- **Connect Power BI to PostgreSQL** using your preferred connector.
- **Model** relationships and build visuals for customer and transaction dashboards.
- **Add DAX calculated columns and measures** (see samples below).


#### 3. Dashboard Views
- **Customer Dashboard:** Segmentation insights, income bands, education-level, state-wise contribution, satisfaction scores.
- **Transaction Dashboard:** Card usage trends, quarterly revenue, fees/interest, expenditure patterns, acquisition cost, chip/online/swipe analysis.
- **Live Week-on-Week Metrics:** DAX-driven visuals for revenue changes, actionable at a glance.

---

## 📦 Files Included
- `SQL-Query-Financial-Dashboard-Data.sql` – Database schema, CSV import scripts, incremental data load instructions.
- `credit_card.csv`, `customer.csv`, `cc_add.csv`, `cust_add.csv` – Sample datasets, full and incremental.
- Power BI Dashboard Images – Customer and transaction view screenshots.

---

## 💡 Real-World Impact
This dashboard reflects how financial teams track card performance, customer lifetime value, and segment profitability.  
- Powered by **actual data**, **incremental refreshes**, and **DAX logic**.
- Designed for modern BI workflows and for recruiters seeking proven, hands-on skills in SQL, DAX, and Power BI project delivery.
