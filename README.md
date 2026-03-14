# Bike Sales Data Warehouse & Analytics
![Bike Sales Dashboard](Bike%20Sales%20Analysis%20Dashboard.png)
## Project Overview

This project demonstrates the design and implementation of a **Bike Sales Data Warehouse** using **Microsoft SQL Server, SSIS, and Tableau**.
The goal of the project is to build an end-to-end data pipeline that extracts raw sales data, transforms it using ETL processes, stores it in a structured **data warehouse**, and visualizes key business insights through dashboards.

The system enables analysis of:

* Sales performance
* Revenue trends
* Top companies by revenue
* Best performing employees
* Category-wise sales

---

## Tech Stack

* **Database:** Microsoft SQL Server
* **ETL Tool:** SQL Server Integration Services (SSIS)
* **Visualization:** Tableau
* **Data Modeling:** Star Schema (Fact & Dimension Tables)

---

## Data Warehouse Architecture

The data warehouse follows a **Star Schema design** consisting of one fact table and multiple dimension tables.

**Fact Table**

* `BikeSales_Fact`

**Dimension Tables**

* `Employee_Dim`
* `Partner_Dim`
* `Product_Dim`
* `Salesorder_Dim`

These tables enable efficient analytical queries and business intelligence reporting.

---

## ETL Pipeline

The ETL pipeline was developed using **SSIS** to process and load data into the data warehouse.

Key ETL operations include:

* Data extraction from source systems
* Lookup transformations for dimension keys
* Derived column transformations
* Data type conversions
* Loading cleaned data into fact tables

---

## Tableau Dashboard

The Tableau dashboard provides visual insights into bike sales data, including:

* Net revenue by year
* Top 10 companies by revenue
* Best employee by sales
* Top category by sales

These visualizations help identify sales trends and business performance.

---

## Project Structure

```
Bike-Sales-Data-Warehouse
│
├── CREATE DATABASE bikesales_DW Query.txt
├── Dimension_model.png
├── Data Flow.png
├── Bike Sales Analysis Dashboard.png
├── Best Emp by sales.png
├── Net revenue by year.png
├── Top 10 Companies by revenue.png
├── Top category By sales.png
└── README.md
```

---

## Key Features

* Designed a **Star Schema Data Warehouse**
* Implemented **ETL pipelines using SSIS**
* Integrated **fact and dimension tables**
* Built **interactive Tableau dashboards**
* Generated insights for **sales performance analysis**

---

## Author

**Divyesh Soni**
