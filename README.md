# 🔄 ETL Pipeline with Airflow + dbt

🚀 This project demonstrates how to build an **end-to-end ETL pipeline** using:
- **Apache Airflow** for orchestration  
- **dbt (Data Build Tool)** for transformations  
- **Postgres** as the data warehouse  

---

## 📂 Project Overview
1. **Extract** data from a source (CSV, API, or database)  
2. **Load** raw data into Postgres  
3. **Transform** using dbt models (cleaning, aggregations, feature engineering)  
4. **Orchestrate** the pipeline with Airflow DAGs  

---

## ⚙️ Tools & Tech
- Python  
- Apache Airflow  
- dbt  
- Postgres  
- Docker  

---

## 🛠 How to Run
```bash
# Clone repo
git clone https://github.com/YOUR-USERNAME/etl-airflow-dbt.git
cd etl-airflow-dbt

# Install requirements
pip install -r requirements.txt

# Start services
docker-compose up -d
