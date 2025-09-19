# AutoDQ - Automated Databricks Data Quality Framework (Databricks + YAML + PySpark)

A **scalable and reusable framework** to automate **data quality checks** in Databricks.  
This project enables data teams to define validation rules in a simple **YAML configuration file** and execute them at scale using **PySpark**. Validation results are logged in **Delta Lake** for auditing and trend analysis, ensuring data reliability and integrity across the pipeline.  


## Project Overview
Data quality is critical for trustworthy analytics. This framework provides:  
- A **YAML-driven rule engine** to validate datasets.  
- Automated execution as a **Databricks Job**.  
- **Centralized logging** of validation results in Delta tables.  
- Scalable PySpark implementation for large datasets.  

The system is designed for **scalability, reusability, and governance**, making it a strong foundation for enterprise-grade data validation.  

## Key Features
- **Configurable Rules** – Define checks for uniqueness, completeness, validity, and row counts directly in a YAML file.  
- **Automated Execution** – Run seamlessly as a scheduled Databricks Job.  
- **Centralized Logging** – Store validation results in a Delta table for historical audits and quality trend monitoring.  
- **Scalable** – PySpark implementation ensures efficient handling of large datasets.  

##  Tech Stack
- **Databricks** – Core execution platform  
- **PySpark** – Scalable data processing  
- **Delta Lake** – Reliable storage & logging of validation results  
- **YAML** – Externalized configuration for flexible rules  

## 📂 Repository Structure
