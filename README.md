# Online Retail Analysis (SQL + Python + Tableau)

## Project Overview
This project is an end-to-end analysis of the **Online Retail II dataset**.  
It demonstrates skills in **SQL, Python, and Tableau** by cleaning and analyzing real-world transaction data from a UK-based e-commerce retailer.  
The aim is to uncover insights on **sales performance, customer behavior, segmentation, and retention** — core responsibilities of a Junior Data Analyst.

---

## Dataset Information
**Abstract**: A real online retail transaction dataset covering two years.  
**Period**: 01/12/2009 – 09/12/2011  
**Company**: UK-based, non-store online retail selling unique all-occasion giftware.  
**Note**: Many customers are wholesalers.  
**Source**: Dr. Daqing Chen, MSc Data Science, London South Bank University.  

**Attributes:**
- `InvoiceNo` – Transaction ID (if starts with "C", it indicates a cancellation)  
- `StockCode` – Unique product code  
- `Description` – Product name  
- `Quantity` – Number of items per transaction  
- `InvoiceDate` – Date & time of transaction  
- `UnitPrice` – Price per unit (GBP £)  
- `CustomerID` – Unique customer ID  
- `Country` – Customer’s country  

---

## Tools & Technologies
- SQL (SQLite / PostgreSQL) → data cleaning, KPI queries, cohort preparation  
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn) → EDA, RFM segmentation, cohort analysis  
- Tableau → interactive dashboards (Sales, Segmentation, Retention)  

---

## Project Structure
data/  
　- online_retail_II.xlsx (raw data)  
　- online_retail_clean.csv (cleaned data)  

sql/  
　- 01_schema.sql  
　- 02_cleaning.sql  
　- 03_kpi_queries.sql  

notebooks/  
　- 01_eda.ipynb  
　- 02_rfm_cohort.ipynb  
　- 03_basket_analysis.ipynb  

tableau/  
　- OnlineRetailII.twbx  

images/  
　- dashboard_screenshot.png  

README.md  

---

## Analysis Roadmap
1. Data Cleaning – handle cancellations, remove nulls, create revenue column  
2. Exploratory Data Analysis (Python) – trends, top products, country insights  
3. Customer Segmentation (RFM) – Recency, Frequency, Monetary scoring  
4. Cohort & Retention Analysis – customer retention heatmaps  
5. Tableau Dashboards – interactive visuals for business insights  

---

## Example Dashboards
(to be added once Tableau dashboards are ready)  

---

## Key Outcomes
- Built an end-to-end pipeline: SQL → Python → Tableau  
- Derived insights on sales trends, customer behavior, and retention  
- Demonstrated Junior Data Analyst level skills across tools  

---

## Author
Efe Taşdelen
Junior Data Analyst | Industrial Engineer 
