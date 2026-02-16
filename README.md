# AzureDatabricks-Formula1-Project

# 🏎️ Real-World Formula 1 Data Engineering Project on Azure Databricks & Spark

This project demonstrates a **real-world, end-to-end data engineering pipeline** built using **Azure Databricks**, leveraging **Formula 1 racing datasets (1950–2020)**.

The solution follows the **Medallion Architecture (Bronze → Silver → Gold)** and integrates core Azure services such as **Azure Data Lake Gen2**, **Azure Data Factory**, **Delta Lake**, **Unity Catalog**, **Azure Key Vault**, and **Power BI**.

It showcases complete data lifecycle management including ingestion, transformation, optimization, governance, and analytics — all implemented using a modern **Lakehouse architecture**.

---

## 👩‍💻 Author

**Sabino Vas**  
📫 Email: sabinovas007@gmail.com 
🔗 LinkedIn: www.linkedin.com/in/sabino-vas  
💻 GitHub: https://github.com/sabinovas  

---

## 🔧 Project Architecture

- **Azure Data Lake Gen2** – Cloud-based scalable storage  
- **Azure Databricks** – Distributed processing using PySpark & Spark SQL  
- **Delta Lake** – ACID-compliant tables with versioning and time travel  
- **Unity Catalog** – Centralized metadata, lineage, and access control  
- **Azure Data Factory** – Orchestration, scheduling, and monitoring  
- **Azure Key Vault** – Secure secrets and credentials management  
- **Power BI** – Interactive dashboards and analytics  

---

## 🗂️ Workflow Breakdown

### 1️⃣ Data Ingestion (Bronze Layer)

- Ingested structured datasets (CSV/JSON) from Formula 1 history  
- Stored raw data in **Azure Data Lake Gen2** using Delta format  
- Implemented **incremental ingestion** using ADF pipelines  

---

### 2️⃣ Data Transformation (Silver Layer)

- Performed data cleansing and enrichment using **PySpark**  
- Applied joins, aggregations, window functions, and filters  
- Standardized schemas and handled missing or invalid records  

---

### 3️⃣ Analytics Layer (Gold Layer)

- Created curated business tables for analytics  
- Generated metrics such as:
  - Top drivers and constructors by decade  
  - Fastest tracks and lap performance  
  - Championship points analysis  
- Optimized tables for BI consumption  

---

### 4️⃣ Data Governance

- Implemented **Unity Catalog** for:
  - Metadata management  
  - Data lineage tracking  
  - Role-based access control  
- Structured catalogs, schemas, and tables  

---

### 5️⃣ Time Travel & Optimization

- Enabled **Delta Lake Time Travel** for historical queries  
- Used **OPTIMIZE** and **VACUUM** for performance tuning  
- Ensured reliability using ACID transactions  

---

### 6️⃣ Orchestration & Automation

- Designed **ADF pipelines** to trigger Databricks notebooks  
- Parameterized workflows for reusability  
- Implemented retry logic and dependency handling  

---

### 7️⃣ Visualization & Reporting

- Built interactive **Power BI dashboards**  
- Connected directly to curated Delta tables  
- Delivered insights such as:
  - Driver dominance trends  
  - Lap time performance  
  - Race location distribution  
  - Year-over-year comparisons  

---

## 💡 Key Features

- End-to-end **Medallion Architecture** (Bronze → Silver → Gold)  
- Distributed transformations using **PySpark & Spark SQL**  
- **Delta Lake** ACID tables with time travel  
- Enterprise-grade **data governance with Unity Catalog**  
- Automated orchestration using **ADF pipelines**  
- Real-time analytics via **Power BI dashboards**  

---
