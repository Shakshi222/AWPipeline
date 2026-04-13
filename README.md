# Overview

This project demonstrates the design and implementation of an end-to-end data engineering pipeline using Azure services. The pipeline ingests raw data from a Kaggle dataset, performs data cleaning and transformation, and stores the processed data in a structured format for downstream analytics.

# Architecture

Workflow:

Data Ingestion → Kaggle Dataset
Storage → Azure Data Lake Storage Gen2 (ADLS Gen2)
Processing → Azure Databricks (PySpark)
Orchestration → Azure Data Factory (ADF)

Data Layers:

Raw Layer → Original data as ingested
Processed Layer → Cleaned and transformed data
Curated Layer → Analytics-ready dataset
🛠️ Tech Stack
Programming: Python (PySpark)
Cloud Platform: Microsoft Azure
Services Used:
Azure Data Factory (ADF)
Azure Data Lake Storage Gen2 (ADLS Gen2)
Azure Databricks
Tools: Git, VS Code
⚙️ Pipeline Workflow
Ingested the dataset from Kaggle into ADLS Gen2
Designed ADF pipelines to automate data movement
Cleaned and transformed data using PySpark:
Handled missing values
Removed duplicates
Standardized data formats
Stored processed data into structured layers in ADLS
├── README.md
# Key Features
End-to-end ETL pipeline on the cloud
Scalable data storage using ADLS Gen2
Automated workflows using ADF triggers
Modular and layered data architecture
# Future Enhancements
Add CI/CD pipeline using Azure DevOps or GitHub Actions
Integrate Power BI for data visualization
Implement data validation and monitoring
Optimize performance using partitioning and caching
# How to Run
Upload dataset to ADLS Gen2
Configure the Azure Data Factory pipeline
Run the Databricks notebook for transformation
Trigger the pipeline manually or schedule it
