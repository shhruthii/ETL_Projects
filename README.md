# ETL_Projects

This repository showcases a collection of ETL (Extract, Transform, Load) pipelines built with Python, focusing on end-to-end data workflows. The projects demonstrate how to connect to SQL Server and other relational databases, extract raw data, transform it into structured formats using pandas, and load it into a PostgreSQL warehouse for analytics and reporting.

🔹 Key Highlights

Built modular ETL pipelines (extract, transform, load) using Python.

Connected securely to SQL Server and PostgreSQL with pyodbc and SQLAlchemy.

Automated data extraction for both reference/master data (e.g., product categories, territories) and transactional data (e.g., sales facts).

Implemented batch inserts, error handling, and environment variable authentication for scalable and secure pipelines.

Designed pipelines for different use cases, including:

General ETL Pipeline (end-to-end data flow)

Database Connection Setup (Python ↔ SQL Server)

Reference Data Loading (consistent lookup/master tables)

GPC Extract & Load (handling hierarchical classification data)

🔹 Tech Stack

Python (pandas, SQLAlchemy, pyodbc)

SQL Server (source system)

PostgreSQL (target data warehouse)

Environment Variables (secure credential management)
