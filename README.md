# BI_Pipeline
This project demonstrates an end-to-end Business Intelligence (BI) pipeline using Microsoft tools, including ETL processing, data warehouse design, cube modelling, and dashboard reporting.

## Project Overview
The goal of this project is to transform raw data into meaningful business insights by building a complete BI workflow.

The project includes:
- Extract, Transform, Load (ETL) using SSIS
- Star schema data warehouse design
- Cube data model using SSAS
- Interactive dashboard using Power BI

## Tools & Technologies
- SQL Server
- SSIS (SQL Server Integration Services)
- SSAS (SQL Server Analysis Services)
- Power BI

## ETL Process
- Loaded data from multiple source files (Customer, Product, Store, Time, Fact)
- Performed data type conversions
- Stored cleaned data into SQL Server database

## Star Schema
- Created fact table: **FactTable**
- Created dimension tables:
  - DimCustomer
  - DimProduct
  - DimStore
  - DimTime
- Established primary and foreign key relationships

## Cube Model (SSAS)
- Built multidimensional cube
- Enabled analysis across:
  - Time
  - Customer
  - Product
  - Store

## Power BI Dashboard
- The dashboard provides includes multiple visualizations to analyse sales performance.
  <img width="1002" height="528" alt="image" src="https://github.com/user-attachments/assets/6b915160-a4c8-4d19-9a96-2f820081be79" />


## Note
This project was completed as part of COMP6350 coursework (Semester 1, 2026).
