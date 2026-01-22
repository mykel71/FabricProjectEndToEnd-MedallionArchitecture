# 🚀 Microsoft Fabric End-to-End Data Engineering Project

## Implementing Medallion Architecture (Bronze, Silver, Gold)

## 📌 Overview

This repository contains an **end-to-end real-world Data Engineering project** built using **Microsoft Fabric**.
The project demonstrates how to design and implement the **Medallion Architecture (Bronze, Silver, Gold layers)** using **Fabric Lakehouse, Data Pipelines, PySpark Notebooks, Semantic Models, and Power BI**.

It is designed for:

* Data Engineers
* Data Analysts
* BI Engineers
* Analytics & Business Users
* Anyone learning Microsoft Fabric

No prior experience with Microsoft Fabric is required.

---

## 🏢 Business Scenario

### **E-commerce Business Performance & Customer Engagement Analysis**

A mid-sized retail company (**ShoppingMart**) is experiencing increased competition and needs deeper insights into:

* Customer purchasing behavior
* Sales performance
* Inventory management
* Online engagement
* Product sentiment

The goal is to build a **modern, scalable analytics solution** that integrates **structured and unstructured data** to generate **actionable insights and business KPIs**.

---

## 🎯 Project Objectives

* Ingest **structured (CSV)** and **unstructured (JSON)** data
* Store raw data in a **Fabric Lakehouse**
* Implement **Bronze, Silver, and Gold** layers using Delta tables
* Orchestrate pipelines using **Fabric Data Factory**
* Transform data using **PySpark notebooks**
* Build a **Semantic Model** for analytics
* Create **Power BI reports** with real-world KPIs

---

## 🧱 Architecture – Medallion Design

```
Data Sources
   │
   ▼
Fabric Data Pipeline
   │
   ▼
Bronze Layer (Raw Data - Lakehouse)
   │
   ▼
Silver Layer (Validated & Cleaned Data - PySpark)
   │
   ▼
Gold Layer (Aggregated & Business-Ready Data)
   │
   ▼
Semantic Model
   │
   ▼
Power BI Reports
```

---

## 🔧 Technologies Used

* **Microsoft Fabric**

  * Fabric Lakehouse
  * Fabric Data Factory
  * Fabric Data Engineering
* **Delta Lake**

  * Delta Parquet Format
  * ACID Transactions
* **PySpark**
* **Power BI**
* **Semantic Models**
* **GitHub (Version Control)**

---

## 📂 Repository Structure

```
📁 data
│   ├── structured
│   │   ├── transactions.csv
│   │   ├── inventory.csv
│   │
│   ├── unstructured
│       ├── reviews.json
│       ├── web_logs.json
│
📁 notebooks
│   ├── silver_layer_transformations.ipynb
│   ├── gold_layer_aggregations.ipynb
│
📁 pipelines
│   ├── fabric_data_pipeline.json
│
📁 semantic_model
│   ├── model_definition
│
📁 reports
│   ├── power_bi_report.pbix
│
📄 README.md
```

---

## 📁 Dataset Details

The datasets used in this project include:

### Structured Data (CSV)

* Sales transactions
* Product inventory

### Unstructured Data (JSON)

* Customer reviews
* Web and engagement logs

These datasets simulate real-world enterprise data sources.

---

## 🔹 What This Project Covers

* Microsoft Fabric fundamentals
* Lakehouse architecture using Delta tables
* Medallion Architecture (Bronze, Silver, Gold)
* Metadata-driven pipeline orchestration
* Data transformation using PySpark
* Building analytics-ready Gold tables
* Creating a Semantic Model
* Building Power BI dashboards with KPIs

---

## 📊 KPIs & Insights Delivered

* Total Sales & Revenue Trends
* Customer Purchase Behavior
* Inventory Availability & Stock Movement
* Product Performance
* Engagement & Sentiment Analysis

---

## 🚀 How to Use This Repository

1. Clone the repository:

   ```bash
   git clone https://github.com/mykel71/microsoft-fabric-medallion-project.git
   ```

2. Upload datasets to **Microsoft Fabric Lakehouse**

3. Create Fabric Pipelines using provided metadata

4. Run PySpark notebooks for Silver & Gold layers

5. Build the Semantic Model

6. Open Power BI report and refresh data

---

## 💡 Why Microsoft Fabric?

Microsoft Fabric is an **all-in-one analytics SaaS platform** that unifies:

* Power BI
* Azure Synapse Analytics
* Azure Data Factory

into a single, seamless experience for data engineering, analytics, and BI.

---

## 📌 Prerequisites

* Microsoft Fabric enabled tenant
* Basic SQL or PySpark knowledge (recommended)
* Power BI access


### 🔥 Happy Learning & Building with Microsoft Fabric!

