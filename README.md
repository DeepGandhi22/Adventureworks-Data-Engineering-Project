# AdventureWorks Data Engineering Project

## Goal

The main objective of this project is to build an **end-to-end data pipeline** to extract, transform, and prepare data for **analysis** and **reporting**. The project leverages several Azure services to ensure scalability, reliability, and performance across the pipeline.

---

## Technologies & Services Used

- **Azure SQL Database** – For data storage  
- **Azure Data Factory** – For orchestration and pipeline creation  
- **Azure Synapse Analytics** – For querying and creating views over datasets  
- **Azure Databricks** – For advanced data transformation  

---

## 🔄 Project Workflow

### 🔹 1. Data Flow Architecture

The pipeline integrates multiple services to process data from ingestion to analysis. Below is a high-level architectural overview:

![AdventureWorks Architecture](https://github.com/user-attachments/assets/594bf0d2-524d-433a-a7f2-8fdcdbc3aff4)

---

### 2. Azure Data Factory

Azure Data Factory (ADF) was used to orchestrate the data pipeline, enabling automated extraction and movement of data between services.

![ADF Screenshot](https://github.com/user-attachments/assets/c862b7f4-458a-44ae-83e9-47755e6b5bd6)

---

### 3. Azure Synapse Analytics

Data from the Azure SQL Database was analyzed and organized into views using **Azure Synapse Analytics**, facilitating easier reporting and visualization.

![Synapse Screenshot](https://github.com/user-attachments/assets/a8505ea8-a998-402d-bd4e-e2c21fe7abaf)

---

## Summary

This project showcases the implementation of a **complete data engineering pipeline** using the Azure ecosystem. From data ingestion with **ADF** to transformation with **Databricks**, and finally analysis through **Synapse Analytics**, this pipeline ensures clean, structured, and report-ready data for business intelligence use cases.
