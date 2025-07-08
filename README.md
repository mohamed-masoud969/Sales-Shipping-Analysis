# 📊 Superstore Sales Analysis (2015–2018)

This project presents a technical data analysis of Superstore sales data between 2015 and 2018. The analysis was performed using Power BI, with a strong focus on data cleaning, modeling, and uncovering insights to support data-driven business decisions.

---

## 🎯 Project Objectives

- Analyze sales performance and trends over time  
- Identify top-performing product categories and regions  
- Explore customer behavior and engagement  
- Calculate key metrics such as Recency, Frequency, Retention, and Average Order Value  
- Build an interactive report using Power BI for business users

---

## 🛠 Tools & Technologies Used

- Microsoft Excel — raw data source (.xlsx)  
- SSIS (SQL Server Integration Services) — for data cleaning (handling duplicates, fixing Product IDs)  
- Power Query — for data transformation and building the Date dimension  
- DAX (Data Analysis Expressions) — for calculating KPIs and customer metrics (RFM, AOV, Retention, etc.)  
- Power BI Desktop — for data modeling, visualizations, and dashboard development  
- Git & GitHub — for version control and sharing the project

---

## 🧱 Data Model

The dataset was organized into a star schema with the following structure:

- Fact Table: Sales Transactions  
- Dimension Tables: Product, Customer, Region, Date  

This model enables flexible time-based and regional analysis.

---

## 📈 Key Insights

- Most profitable regions and cities were identified  
- Top-selling categories and sub-categories were ranked  
- Customer activity was segmented based on Recency and Frequency  
- Shipping modes were analyzed for impact on performance  
- Dynamic metrics built using DAX enhanced report interactivity

---

## 📁 Project Files
- 📊 [View Power BI Reprot](https://app.powerbi.com/reportEmbed?reportId=5ae76080-1b8a-4e53-bff8-92c6201b2b28&autoAuth=true&ctid=3c7a4dad-22f9-460f-9b04-70b4ea89f49f)
> Note: Open the .pbix file using Power BI Desktop to explore the full report and metrics.
