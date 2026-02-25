# 🏗️ End-to-End Data Warehouse & ETL Pipeline Project

This project demonstrates the design and implementation of a full **Data Warehouse architecture** using Microsoft BI tools — including **ETL with SSIS**, **reporting with SSRS**, and a **star schema** data model.

---

## 📦 Project Overview

**Domain:** Sales
**Goal:** Build a scalable and efficient data warehouse pipeline from raw transactional data to analytical reports.

---

## 🧩 Components

### 1. Data Storage & Staging
- Source data ingested into staging tables using flat files or OLEDB.
- Cleaned and validated using SQL scripts.

### 2. ETL Process (SSIS)
- **Tool:** SQL Server Integration Services (SSIS)
- Steps:
  - Extract from source (CSV/Excel/DB)
  - Apply transformation rules (type conversions, lookups, joins)
  - Load into staging → dimension → fact tables
- **File:** Located in `/SSIS_Package/`

### 3. Data Warehouse Design
- **Schema:** Star Schema  
- **Fact Table:** [e.g., FactSales]  
- **Dimension Tables:** DimDate, DimCustomer, DimProduct, etc.
- **File:** Diagram available in `/Star_Schema_Diagram/`

### 4. Reporting (SSRS)
- Built dashboards and paginated reports with KPIs.
- Exported samples available in `/SSRS_Reports/`

---

## ⚙️ Technologies Used

| Tool/Tech | Purpose |
|----------|---------|
| SQL Server | Data warehouse and staging |
| SSIS | ETL workflows |
| SSRS | BI reporting |
| T-SQL | Data modeling & transformation |
| Star Schema | DW modeling technique |

---

## 📁 Folder Structure

