
# 🚀 Azure Data Engineering Project : Advanced ADF Pipelines

---

## 🧩 Overview

This repository contains an **advanced Azure Data Factory project** that explores how to design and automate **modern data pipelines**.  
The goal is to practice real-world data engineering scenarios — including **incremental ingestion**, **API data integration**, and **GitHub CI/CD** — while following Azure best practices.

It’s a learning-oriented, hands-on project inspired by professional Azure Data Engineering workflows.

---

## 🎯 Main Objectives

- Build and orchestrate pipelines in **Azure Data Factory (ADF)**
- Connect to **Azure SQL Database** as a destination
- Ingest data from multiple sources (flat files, REST APIs)
- Implement **incremental loading** with JSON watermarks
- Handle **pagination** and **API parameters** dynamically
- Use **ADF variables, parameters, ForEach, and Lookup** activities
- Integrate ADF with **GitHub** for version control and CI/CD

---

## 🧱 Project Components Implemented

| Component | Description |
|------------|-------------|
| **Azure Data Factory** | Main orchestration service (pipelines, datasets, linked services) |
| **Azure SQL Database** | Target data store for ingestion and transformations |
| **REST API Source** | Example of external data ingestion (with pagination logic) |
| **GitHub Integration** | Source control, branching, and CI/CD setup |
| **Incremental Ingestion** | Load new data using JSON-based watermark tracking |

---

## 🏗️ Project Architecture (Practical Overview)

The architecture below represents what was implemented in this project and how it connects in a realistic enterprise context.

```mermaid
graph TD
A[Source Data (CSV / REST API)] -->|Copy Activity| B[Azure Data Factory Pipelines]
B -->|Incremental Load| C[Azure SQL Database]
B -->|Version Control| D[GitHub Repository]
C -->|Data Ready for Analysis| E[Power BI / Analytics Tools (Optional)]
