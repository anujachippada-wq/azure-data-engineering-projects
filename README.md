# azure-data-engineering-projects
Azure Data Engineering Projects
# 🚀 Azure Data Engineering Projects

This repository contains end-to-end data engineering projects built using Azure services, following modern data architecture principles like Medallion Architecture (Bronze, Silver, Gold).

---

## 📌 Projects Included

### 1️⃣ Azure Data Factory (ADF) Integration Project

### 🔹 Overview

This project demonstrates an ETL pipeline using Azure Data Factory to ingest, transform, and load data from multiple sources into Azure SQL Database.

### 🛠️ Tools Used

* Azure Data Factory
* Azure Data Lake Storage Gen2
* Azure SQL Database
* Azure Key Vault
* SQL Server

### 🔄 Architecture Flow

* REST API → Azure SQL Database
* On-Prem SQL Server → ADLS Gen2 (Bronze Layer)
* Data stored in Parquet format
* Data cleaned → Silver Layer
* SCD Type 1 & Type 2 applied
* Final data → Gold Layer (Azure SQL Database)

---

### 2️⃣ Azure Databricks Medallion Architecture Project

### 🔹 Overview

This project processes banking data using Azure Databricks and implements Medallion Architecture for scalable data transformation.

### 🛠️ Tools Used

* Azure Data Lake Storage Gen2
* Azure Databricks
* Databricks Notebooks
* Power BI

### 🔄 Architecture Flow

* Raw data → Bronze Layer
* Data cleaning → Silver Layer
* Business transformation → Gold Layer
* Reporting → Power BI Dashboard

---

## 🧱 Architecture Pattern Used

### Medallion Architecture:

* **Bronze** → Raw data
* **Silver** → Cleaned data
* **Gold** → Business-ready data

---

## 📊 Key Features

* End-to-end ETL pipelines
* Data validation & cleaning
* Slowly Changing Dimensions (SCD Type 1 & 2)
* Secure credential management using Key Vault
* Scalable and modular design

---

## 📁 Repository Structure

```bash
azure-data-engineering-projects/
│── README.md
│── ADF_Project.docx
│── Databricks_Project.docx
```

---

## 📌 Future Enhancements

* Add real-time data pipelines
* Integrate CI/CD using Azure DevOps
* Add pipeline monitoring & alerting

---

## 👩‍💻 Author

**Anuja Chippada**
