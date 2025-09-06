# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse using **Medallion Architecture** (Bronze, Silver, and Gold layers).  
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.  
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.  
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.  

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- **SQL Development**  
- **Data Architect**  
- **Data Engineering**  
- **ETL Pipeline Development**  
- **Data Modeling**  
- **Data Analytics**  

---
## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.  
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.  
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.  
- **Scope**: Focus on the latest dataset only; historization of data is not required.  
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.  

---
## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture** — **Bronze, Silver, and Gold layers**:

<img width="971" height="542" alt="ETL Map-Page-2 drawio" src="https://github.com/user-attachments/assets/68684574-a141-4ff8-87dd-169f778f3a9b" />  

### 🔸 Data Warehouse

**1. Bronze Layer**  
- Stores raw data *as-is* from the source systems.  
- Data is ingested from CSV files into SQL Server Database.  
- **Object Type**: Tables  
- **Load**: Batch Processing, Full Load, Truncate & Insert  
- **Transformations**: None  
- **Data Model**: None (as-is)  

**2. Silver Layer**  
- Includes **data cleansing, standardization, and normalization** processes to prepare data for analysis.  
- **Object Type**: Tables  
- **Load**: Batch Processing, Full Load, Truncate & Insert  
- **Transformations**:  
  - Data Cleansing  
  - Data Standardization  
  - Data Normalization  
  - Derived Columns  
  - Data Enrichment  
- **Data Model**: None (as-is)  

**3. Gold Layer**  
- Houses **business-ready data** modeled into a star schema required for reporting and analytics.  
- **Object Type**: Views  
- **Load**: No Load  
- **Transformations**:  
  - Data Integrations  
  - Aggregations  
  - Business Logic  
- **Data Model**:  
  - Star Schema  
  - Flat Table  
  - Aggregated Table  

### 📊 Consumption
- **BI & Reporting**  
- **Ad-hoc SQL Queries**  
- **Machine Learning**  

---
### BI: Analytics & Reporting (Data Analytics)

**Objective**  
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**  
- **Product Performance**  
- **Sales Trends**  

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---

## 📝 License

This project is licensed under the [MIT License](./LICENSE). You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

Hi, I'm **Rishikesh Singh** — a **Power BI Developer** and data enthusiast passionate about transforming raw data into actionable business insights.  

I specialize in:  
- **Data Visualization & BI**: Building interactive dashboards in Power BI that drive informed decision-making.  
- **Data Engineering Foundations**: Designing and optimizing data models, ETL processes, and SQL-based solutions.  
- **Analytics & Reporting**: Delivering insights on sales, customer behavior, and business performance.  

Beyond work, I run a YouTube channel called **DataMinds Academy**, where I create beginner-to-advanced tutorials on Power BI, SQL, and data analytics concepts — helping thousands of learners grow their skills.  

I’m continuously expanding my expertise into **Data Engineering and Cloud Technologies**, aiming to design scalable data solutions for modern businesses. My mission is to **make data simple, insightful, and impactful**.  

