# Azure Data Engineering Project

This repository is part of a **full-stack Azure Data Engineering project**, combining:

1. **Azure Data Factory (ADF) pipelines** – ingest, orchestrate, and pre-process source data  
2. **Azure Databricks notebooks** – perform **SCD1 & SCD2 transformations** on a **Medallion Architecture (Bronze → Silver → Gold)**

> The workflow starts with **ADF pipelines**, followed by **Databricks transformations**.

---

## 📁 Repository Links

- **ADF pipelines (ETL orchestration, linked services, triggers)** → This repository: [ADF_REPO](https://github.com/pranavprasanth14/ADF_REPO)  
- **Databricks (SCD1/SCD2, Medallion Architecture)** → [ADB_REPO](https://github.com/pranavprasanth14/ADB_REPO)

---

## 🚀 Project Overview

**ADF pipelines (Step 1):**  

- Ingest data from various sources  
- Perform preliminary transformations  
- Store curated datasets in landing / staging zones  
- Schedule pipelines using triggers  

**Databricks notebooks (Step 2):**  

- Bronze Layer: Ingest pre-processed data from ADF outputs  
- Silver Layer: Apply SCD1 & SCD2 logic for historical tracking and updates  
- Gold Layer: Produce analytics-ready datasets for reporting/BI  

---

## 📌 How to Use

1. Clone this repo (ADF pipelines) and explore datasets, pipelines, and triggers:  
   git clone https://github.com/pranavprasanth14/ADF_REPO.git
2. After running ADF pipelines, clone the Databricks repo to perform SCD transformations:
   git clone https://github.com/pranavprasanth14/ADB_REPO.git





💡 Author

Pranav Prasanth – Azure Data Engineering & Databricks enthusiast

#AzureDataFactory #AzureDatabricks #SCD1 #SCD2 #MedallionArchitecture #DataEngineering
