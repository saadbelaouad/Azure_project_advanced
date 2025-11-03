
# 🚀 Azure Data Engineering Project : Advanced ADF Pipelines


## Overview

This repository contains an **advanced Azure Data Factory project** that explores how to design and automate **modern data pipelines**.  
The project is a hands-on implementation inspired by **real-world enterprise data engineering workflows** and Azure best practices.

## Main Objectives

- Build and orchestrate pipelines in **Azure Data Factory (ADF)**
- Integrate **Azure SQL Database** for data storage and transformations
- Ingest data from multiple sources (**CSV**, **REST APIs**, etc.)
- Implement **incremental loading** using **JSON watermarks**
- Handle **pagination** and dynamic API parameters
- Leverage **ADF activities** such as Lookup, ForEach, Switch, and Validation
- Store processed data in **Delta Lake** format
- Add **pipeline validation and monitoring** with **email alerts**
- Integrate with **GitHub** for version control and **CI/CD deployment**

## Project Components Implemented

| Component | Description |
|------------|-------------|
| **Azure Data Factory** | Central orchestration service (pipelines, datasets, linked services) |
| **Azure SQL Database** | Target data store for structured ingestion and transformation |
| **Delta Lake** | Reliable file storage with ACID transactions and schema evolution |
| **REST API Source** | External data ingestion with pagination and dynamic parameters |
| **Pipeline Validation** | Post-load checks for data quality and completeness |
| **Email Alerts** | Automated notifications using **Logic Apps / Azure Monitor** |
| **GitHub Integration** | Source control, versioning, and CI/CD configuration |
| **Incremental Ingestion** | Load only new or changed data via JSON watermark logic |

---

