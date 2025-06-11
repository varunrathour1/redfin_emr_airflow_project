# 🏘️ Redfin Real Estate Data Engineering Project

This project demonstrates an end-to-end data engineering pipeline using Redfin real estate data. It covers ingestion, transformation, storage, and visualization using industry-grade tools.

---

## 🛠️ Tools & Technologies Used

- **Apache Airflow** – Workflow orchestration
- **Amazon EMR** – Cluster processing
- **Python** – Data transformation scripts
- **Snowflake** – Data warehousing
- **Power BI** – Business Intelligence (dashboard not included here)
- **Shell Scripting** – Automation
- **Pandas, NumPy** – Data wrangling libraries

---

## 📊 Project Architecture

![Architecture Diagram](project%20architecture.png)

---

## 📊 Project Video
![Project Video](redfin_data_analysis.MP4)
---

## 1️⃣ Data Ingestion

- `ingest.sh` – Shell script to fetch and stage data.
- `commands_run.txt` – Logs of commands run during EMR execution.
- Airflow DAG (assumed) runs and schedules the ingestion pipeline.

---

## 2️⃣ Data Transformation

- `transform_redfin_data.py` – Cleans, enriches, and structures raw data.
- `redfin_analytics.py` – Optional additional analytics logic.
- Libraries used: `pandas`, `numpy`.

---

## 3️⃣ Data Storage - Snowflake

- `snowflake script.txt` – Contains SQL scripts to create Snowflake DB, schemas, and tables.
- Follows **SCD Type 2** practices for handling slowly changing dimensions.

---

## 4️⃣ Analytics Layer (Power BI)



Key visuals included:
- Region-wise price analysis  
- Time series of median sale prices  
- Active listings and sales comparison  

---

## 📎 Supporting Material

- [Redfin_Project_Architecture_PPT_Varun.pptx](Redfin_Project_Architecture_PPT_Varun.pptx) – Project slides (optional to include)

---


