# Online Retail Analysis (SQL + Python + Tableau)

## Project Overview
This project is an end-to-end data analysis of the **Online Retail II dataset**, focusing on customer behavior, sales performance, and retention.  
The analysis integrates **SQL (data cleaning & KPIs)**, **Python (EDA, RFM, cohort analysis)**, and **Tableau (interactive dashboards)**.  
The goal is to demonstrate practical skills in **data extraction, transformation, analysis, and visualization** — key competencies for a **Junior Data Analyst**.

---

## Dataset Information
**Abstract**: A real online retail transaction dataset of two years.  
**Source**: Dr. Daqing Chen, MSc Data Science, London South Bank University.  

- **Period**: 01/12/2009 – 09/12/2011  
- **Company**: UK-based, non-store online retail selling unique all-occasion giftware.  
- **Notes**: Many customers are wholesalers.  

**Attributes:**
- `InvoiceNo` – Transaction ID (if starts with "C", it’s a cancellation)  
- `StockCode` – Unique product code  
- `Description` – Product name  
- `Quantity` – Quantity of each product per transaction  
- `InvoiceDate` – Date & time of transaction  
- `UnitPrice` – Product price (GBP £)  
- `CustomerID` – Unique customer ID  
- `Country` – Customer’s country  

---

## Tools & Technologies
- **SQL (SQLite / PostgreSQL)** → Data cleaning, KPI queries, cohort preparation  
- **Python (Pandas, Matplotlib, Seaborn, Scikit-learn)** → EDA, RFM segmentation, cohort analysis  
- **Tableau** → Interactive dashboards (Sales trends, RFM segmentation, Cohort retention)  

---

## Project Structure
📁 data  
　┣  online_retail_II.xlsx (original data)  
　┗  online_retail_clean.csv (clean & organized data)  

📁 sql  
　┣  01_schema.sql  
　┣  02_cleaning.sql  
　┗  03_kpi_queries.sql  

📁 notebooks  
　┣  01_eda.ipynb  
　┣  02_rfm_cohort.ipynb  
　┗  03_basket_analysis.ipynb  

📁 tableau  
　┗ OnlineRetailII.twbx  

📁 images  
　┗ dashboard_screenshot.png  

## Analysis Roadmap
1. **Data Cleaning (SQL & Python)**  
   - Remove nulls, duplicates, invalid transactions (cancellations, negative/zero values).  
   - Create a clean `sales` table with revenue column.  

2. **Exploratory Data Analysis (Python)**  
   - Daily/weekly sales trends  
   - Top products & countries  
   - Outlier detection  

3. **Customer Segmentation**  
   - **RFM Analysis** (Recency, Frequency, Monetary)  
   - Assign segments (Champions, Loyal, At Risk, New, etc.)  

4. **Cohort & Retention Analysis**  
   - Monthly cohorts  
   - Retention heatmaps  
   - Customer Lifetime Value estimation (basic)  

5. **Tableau Dashboards**  
   - **Executive Overview**: Revenue, Orders, AOV trends  
   - **Product & Country Insights**: Top sellers, top markets  
   - **Customer Segmentation**: RFM distribution & revenue share  
   - **Cohort Retention**: Retention heatmap & trends  

---

## Example Dashboard Previews
*(Screenshots will be added after Tableau dashboards are created)*  

---

## Key Outcomes
- End-to-end data pipeline: SQL → Python → Tableau  
- Business insights on **sales trends, customer segments, and retention**  
- Demonstrates core skills expected from a **Junior Data Analyst**  

---
