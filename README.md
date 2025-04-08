# Data Warehouse and Analytics Project
<br>Welcome to the Data Warehouse and Analytics Project repository! 🚀</br>
Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics. This repository also contains a collection of SQL scripts demonstrating various analytical techniques, such as changes over time, cumulative, performance, data segmentation, and part-to-whole analysis.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](Downloads\data_architecture.jpg)

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
