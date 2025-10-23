**Data Warehouse and Analytics Project**

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This is a data engineering and analytics project that is building data pipelines, data warehouses, and analytical models to generate actionable business insights.

The project is designed to showcase industry-standard data warehousing practices, including data architecture design, ETL processes, data modeling, and reporting.




**🏗️ Data Architecture**

The project follows the Medallion Architecture pattern — organized into Bronze, Silver, and Gold layers — to ensure a structured and scalable data flow.

**Bronze Layer**
      Stores raw data as-ingested from the source systems.
      Data is loaded directly from CSV files into the SQL Server database without any transformations.

**Silver Layer**
Cleans, validates, and standardizes the data.
This layer focuses on improving data quality, consistency, and structure to make it ready for analytics.

**Gold Layer**
Contains the final, business-ready data modeled into star schemas.
This is the layer used for reporting, dashboards, and advanced analytics.


**📖 Project Overview**

This project demonstrates the end-to-end process of building a modern data warehouse and analytics system.

**Key Components:**

**Data Architecture –** Designing a multi-layered architecture (Bronze, Silver, Gold).

**ETL Pipelines –** Extracting, transforming, and loading data into a warehouse using SQL scripts.

**Data Modeling –** Developing fact and dimension tables optimized for performance and analysis.

**Analytics & Reporting –** Writing SQL queries and generating insights for decision-making.

**🚀 Project Requirements**
**Data Engineering (Building the Data Warehouse)**

**Objective**
Develop a SQL Server–based data warehouse that integrates multiple datasets into a single analytical model.

**Specifications**

**Data Sources:** Import data from CSV files representing ERP and CRM systems.

**Data Quality:** Identify and fix inconsistencies and missing data.

**Integration:** Merge different data sources into a single unified model.

**Documentation:** Maintain detailed documentation of data models and transformations.

**Scope:** Focused on current datasets (no historical data tracking required).

**Data Analysis (Analytics & Reporting)**

**Objective**
Use SQL-based analytics to uncover insights from the consolidated warehouse.

**Key Focus Areas:**

**Customer Analysis –** Understanding customer distribution and activity.

**Product Insights –** Analyzing product performance and sales trends.

**Sales Reporting –** Tracking overall sales and performance metrics.

These analytics demonstrate how structured data can support data-driven decision-making.
For more details, refer to docs/requirements.md

**📂 Repository Structure**
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
👋 Hi, I’m Chance Zimba, a passionate Data Engineer and Data Scientist with hands-on experience in data warehousing, ETL development, and analytics.

I enjoy building data-driven systems that transform raw data into meaningful insights using modern data tools and techniques.

💡 Interests:
**Data Engineering • Machine Learning • NLP •AI • Business Intelligence • Data Visualization**
