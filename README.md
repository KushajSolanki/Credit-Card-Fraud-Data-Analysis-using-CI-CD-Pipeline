# Credit-Card-Fraud-Data-Analysis-using-CI-CD-Pipeline


## 📌 Project Overview
This project simulates a **Car Rental Data Batch Ingestion Pipeline** with **Slowly Changing Dimension Type 2 (SCD2) merge logic**.  
It demonstrates how to design scalable, production-style **data engineering workflows** using modern cloud tools.  

### 📊 Architecture Diagram
![Car Rental Data Pipeline Architecture](credit-card-analysis.png)

---

## 🛠 Tech Stack
- **Python / PySpark** – Data transformation & processing  
- **Google Cloud Storage (GCS)** – Raw & processed data storage  
- **Dataproc Serverless** – Distributed data processing  
- **BigQuery** – Data warehouse with SCD2 merge logic  
- **Airflow (Cloud Composer)** – Workflow orchestration  
- **GitHub Actions** – CI/CD automation  

---

## ⚙️ Pipeline Workflow
1. **Ingestion**  
   - Car rental bookings & customer data loaded into **GCS**.  

2. **Processing**  
   - Data cleaned & transformed with **PySpark** on **Dataproc Serverless**.  

3. **SCD2 Merge**  
   - Historical changes in customer & car dimension data tracked using **SCD2 logic** in **BigQuery**.  

4. **Orchestration**  
   - Entire pipeline automated & scheduled with **Airflow (Cloud Composer)**.  

5. **CI/CD**  
   - Deployment managed using **GitHub Actions** for version control and automation.  

---

## 📊 Why This Project?
- Preserves **data history** for analytics teams.  
- Demonstrates **real-world data engineering concepts** like ETL, orchestration, and CI/CD.  
- Scalable & cloud-native design.  

---

## 🚀 How to Run
 Clone this repository
