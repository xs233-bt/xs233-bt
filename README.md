## Hi there 👋 I’m Neo (Shunci) Lu

🎯 **Data Engineer | Business Intelligence Analyst @ Scootaround Inc.**  
📍 Canada 🇨🇦 | 🌎 Building scalable data pipelines & analytics systems

---

### 🧠 About Me

- 🔭 Currently working on **data engineering projects** involving **Airflow**, **dbt**, and **AWS** (Glue, Redshift, Athena, S3), with modern table formats such as **Apache Iceberg** and **Delta Lake**
- 🧩 Strong background in **data modeling**, **ETL / ELT automation**, and **financial analytics** (revenue, cost, margin, and profitability reporting)
- ⚙️ Hands-on experience with **Python**, **SQL**, **Power BI**, **Spark**, and **Terraform** to build production-grade data pipelines
- 🚀 Passionate about transforming raw data into actionable insights and enabling **self-serve analytics** at scale

---

### 🏗️ Current Projects

---

### 🔹 IBKR Options Strategy Agent

**Phase I – Completed**

A real-time options analytics engine built in **Python**, leveraging **ib_insync** to interface with the **Interactive Brokers (IBKR) API**. Live option chain data is ingested at near tick-level granularity and streamed through **Apache Kafka** using custom Python producers and consumers. The pipeline computes core option metrics, including **Greeks**, **implied volatility**, **premium yield**, **probability metrics**, and **margin utilization**.

**Phase II – In Progress**

Processed option data is persisted in **Parquet** format on **AWS S3** (with local storage support) and queried using **DuckDB** for high-performance analytics. This phase focuses on generating **systematic strategy signals** for **covered calls**, **cash-secured puts**, and **vertical spreads**, with planned extensions for **historical backtesting**, **portfolio-level risk management**, and **automated trade execution**.

---

### 🔹 Modern Data Lakehouse with Apache Iceberg

Designed and implemented a **schema-evolving data lakehouse** on **AWS**, using **S3 + Glue + Athena + Apache Iceberg**, enabling **versioned, ACID-compliant datasets**.

- Orchestrated **Airflow-based ingestion and transformation pipelines**
- Modeled analytical layers using **dbt** and **Redshift Spectrum**
- Integrated **AWS Glue Data Quality** checks and **SQLMesh backfill automation** to ensure data accuracy, lineage, and reproducibility across a medallion architecture

---

### 🔹 Automated Airflow Reporting via SSH & SMTP

Built a **Python-based ETL pipeline** that securely connects to remote databases via **SSH tunneling**, extracts and transforms daily business data, and distributes formatted reports to stakeholders via email.

- Fully orchestrated with **Apache Airflow** for scheduling, retries, and dependency management
- Implemented using **pandas**, **sshtunnel**, **MySQL Connector**, and **smtplib**
- Enabled reliable, end-to-end reporting automation with zero manual intervention

---

### 🧰 Tech Stack & Tools

**Languages**  
Python | SQL | DAX | YAML | R | Java | Julia

**Data Engineering**  
Airflow | dbt | AWS Glue | Redshift | Athena | S3 | Terraform | Spark | Iceberg | Kafka | SQLMesh

**Analytics**  
Power BI | Tableau | pandas | DuckDB | Trino

**Databases**  
PostgreSQL | MySQL | SQL Server | Redshift Spectrum

**Version Control & Infra**  
GitHub | Docker | Linux | VS Code | AWS CLI

---

### 📚 Certifications & Learning

- 🎓 **Data Engineering Professional Certificate** – DeepLearning.AI
- 🌩️ Currently preparing for **AWS Certified Data Engineer – Associate**
- 🧠 Exploring advanced topics such as **real-time Kafka streaming**, **SQLMesh backfill automation**, and **AI-assisted data operations**

---

### 💬 Let’s Connect

📫 **Email:** [neo.lu.data@gmail.com](mailto:neo.lu.data@gmail.com)  
💼 **LinkedIn:** https://www.linkedin.com/in/neo-lu-4b10171a8  
💻 **GitHub:** https://github.com/xs233-bt

---

### ⚡ Fun Fact

I’ve been playing **Dota** for over 10 years — mastering teamwork, strategy, and the art of not tilting under pressure 😎

---

> _“Standing at the dawn of the fourth technological revolution, I aim to bridge data, intelligence, and automation — shaping a smarter, more connected world.”_ 🌐
