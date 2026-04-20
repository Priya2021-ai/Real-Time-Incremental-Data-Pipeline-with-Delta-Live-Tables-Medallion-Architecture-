# Project Overview
This project demonstrates an end-to-end data pipeline built using Azure Data Factory and Databricks. It follows the Medallion Architecture (Bronze, Silver, Gold) to process incremental data and transform it into a structured format for analytics and reporting.

---

## Architecture
- Data Ingestion using Azure Data Factory
- Incremental data loading into Data Lake Gen2
- Processing using Databricks Autoloader
- Transformation using Delta Live Tables
- Serving layer built using Star Schema
- Data available for reporting (Azure Synapse / BI tools)

---

# Tech Stack
- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2
- Azure Databricks
- Delta Live Tables
- PySpark
- SQL

---

# Pipeline Flow
1. Data is ingested using ADF pipelines
2. Stored in Raw Layer (Bronze)
3. Processed and cleaned into Silver layer
4. Transformed into Gold layer (Star Schema)
5. Data is ready for reporting and analytics

---

# Project Structure
- pipelines/
- datasets/
- linkedServices/
- databricks_notebooks/

---

# Key Features
- Incremental data processing
- Scalable architecture
- Automated pipeline using ADF
- Real-time ingestion with Autoloader
- Structured transformation using Delta Live Tables

---

# Use Case
This pipeline can be used for building real-time analytics systems such as:
- Sales reporting
- Customer insights
- Business intelligence dashboards

---

# Author
Priya
