🚀 ETLWorks SQL Data Warehouse Project

Welcome to the ETLWorks SQL Data Warehouse Project!
This project demonstrates how to build a modern data warehouse in MySQL by applying ETL (Extract, Transform, Load) pipelines and the Medallion Architecture (Bronze, Silver, Gold layers).

ETL is at the core of this project — extracting raw CSV files, transforming them into a clean and reliable structure, and loading them into a business-ready Star Schema for analytics.

🏗️ Data Architecture

This project follows the Medallion Architecture:

Bronze Layer 🥉 → Extract

Loads raw CSV files into staging tables.

Stores data as-is for traceability.

Silver Layer 🥈 → Transform

Cleans, standardizes, and applies business rules.

Ensures consistency and prepares data for modeling.

Gold Layer 🥇 → Load

Models data into Fact & Dimension tables (Star Schema).

Business-ready layer for BI dashboards and analytics queries.

📖 Project Overview

The ETL pipelines are the backbone of this project, ensuring:

Extract → Import CSV files into MySQL.

Transform → Apply cleansing, deduplication, normalization, and business rules.

Load → Deliver analytics-ready Fact & Dimension tables.

By automating ETL, this project guarantees data quality, reliability, and usability for decision-making.

🎯 Skills Demonstrated

✅ ETL Pipeline Development (Extract → Transform → Load)

✅ MySQL Programming (DDL, DML, Views, Stored Procedures)

✅ Data Warehousing (Medallion layered architecture)

✅ Data Modeling (Star Schema with Facts & Dimensions)

✅ Data Quality Checks (referential integrity, duplicates, nulls)

✅ SQL Analytics (Customer behavior, product performance, sales trends)

✅ Version Control (GitHub for collaboration & portfolio showcase)

🛠️ Tools & Tech Stack

MySQL (Database, ETL, Analytics)

MySQL Workbench (Data management & visualization)

CSV Datasets (Raw source files)

Git & GitHub (Version control & project portfolio)

Draw.io (Architecture, ETL flow, Star schema diagrams)

Notion (Project documentation & task tracking)

🚀 Project Requirements
Objective

Build a data warehouse with ETL pipelines in MySQL that integrates raw CSV data to deliver business insights.

Specifications

Sources → CSV files

ETL → Core of the project: Extract, Transform, Load

Integration → Unified star schema for analytics

Data Quality → Enforced via Silver & Gold QC scripts

Documentation → Clear and reusable for learners & professionals

📊 Analytics & Reporting

SQL-based analytics deliver insights into:

👥 Customer Behavior → Segmentation & retention trends

📦 Product Performance → Top-selling categories & margins

📈 Sales Trends → Time-series analysis for growth

📂 Repository Structure
etlworks-sql-dwh/
│
├── datasets/                # Raw CSV datasets
│
├── docs/                    # Documentation & diagrams
│   ├── etl.drawio           # ETL pipeline workflow
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio   # Star schema design
│   ├── naming-conventions.md
│
├── scripts/                 # SQL scripts (DDL, ETL, QC, Views)
│   ├── bronze/              # Extract raw data (staging)
│   ├── silver/              # Transform & clean data
│   ├── gold/                # Load into star schema
│
├── tests/                   # Quality check SQL scripts
│
├── README.md                # Project overview
├── LICENSE                  # License info
└── requirements.txt         # Tools & dependencies

🌟 Key Takeaways

🚀 ETL is the heart of this project: Raw → Clean → Analytics-ready

✅ Built an end-to-end Data Warehouse in MySQL

✅ Applied Medallion Architecture (Bronze → Silver → Gold)

✅ Designed a Star Schema for analytical queries

✅ Automated ETL Pipelines & Quality Checks

✅ Produced business insights from CSV datasets
