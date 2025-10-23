# 🧠 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This is a **personal data engineering and analytics portfolio project** that demonstrates my skills in building **data pipelines**, **data warehouses**, and **analytical models** to generate actionable business insights.  

It follows **industry-standard data warehousing practices** — from data ingestion to analytics — using SQL Server, Python, and visualization tools.

---

## 🏗️ Data Architecture

This project implements the **Medallion Architecture** — structured into **Bronze**, **Silver**, and **Gold** layers — for a clean and scalable data flow.

### 🔹 Bronze Layer
- Stores raw data as-ingested from various source systems.  
- Data is loaded directly from CSV files into the SQL Server database without transformations.

### 🔹 Silver Layer
- Cleans, validates, and standardizes the data.  
- Focuses on data quality, consistency, and preparation for analysis.

### 🔹 Gold Layer
- Contains **business-ready data** modeled into **star schemas**.  
- Supports reporting, dashboards, and advanced analytics.

---

## 📖 Project Overview

This project showcases the **complete data warehousing process** — from raw data ingestion to analytical reporting.

### Key Components
1. **Data Architecture** – Building a multi-layered data warehouse (Bronze, Silver, Gold).  
2. **ETL Pipelines** – Extracting, transforming, and loading data using SQL.  
3. **Data Modeling** – Designing fact and dimension tables for efficient analytics.  
4. **Analytics & Reporting** – Writing SQL queries to extract business insights.

---

## 🚀 Project Requirements

### ⚙️ Data Engineering (Building the Data Warehouse)

**Objective**  
Develop a SQL Server–based data warehouse that consolidates multiple datasets into a unified analytical model.

**Specifications**
- **Data Sources:** Import data from CSV files simulating ERP and CRM systems.  
- **Data Quality:** Identify and clean missing or inconsistent data.  
- **Integration:** Merge multiple sources into a unified, analytics-ready model.  
- **Documentation:** Provide clear and detailed data model documentation.  
- **Scope:** Focused on the current dataset only (no historization required).

---

### 📊 Data Analysis (Analytics & Reporting)

**Objective**  
Use SQL analytics to generate insights from the consolidated warehouse.

**Focus Areas**
- **Customer Analysis** – Understand customer distribution and segmentation.  
- **Product Insights** – Analyze product performance and contribution to sales.  
- **Sales Reporting** – Track sales trends and business performance metrics.

For more details, refer to [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---


---

## 🧰 Tools & Technologies

- **SQL Server** – Data storage, transformation, and modeling  
- **Python (Pandas, Matplotlib)** – Data analysis and automation  
- **Power BI / Excel** – Reporting and visualization  
- **Git & GitHub** – Version control and collaboration  
- **Draw.io** – Data flow and architecture diagramming  

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

👋 Hi, I’m **Chance Zimba**, a passionate **Data Engineer and Data Scientist** with hands-on experience in **data warehousing**, **ETL**, and **data analytics**.  

I enjoy designing and implementing data solutions that transform raw data into powerful business insights.

**💡 Interests:**  
**Data Engineering • Machine Learning • Natural Language Processing • Business Intelligence • Data Visualization**




