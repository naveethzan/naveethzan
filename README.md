# Hey, I'm Naveeth 👋

**Data Engineer** passionate about building **real-time streaming** and **AI-powered data platforms** that scale.

With 4+ years of experience, I love turning messy, fast-moving data into reliable systems and actionable insights.  
Currently **co-founding Zutual AI** (AI-powered life tracking) and previously at **Kovai.co**, where I built a large-scale data infrastructure for *Document360*.

I enjoy working with: **Apache Spark**, **Kafka**, **Airflow**, **DBT**, **AWS**, and exploring the intersection of **AI and modern data engineering**.

---

## 🔧 What I Work On

I build **end-to-end data pipelines** that are production-ready from day one:

- 🏗️ **Data Lakehouse Engineering** – Medallion architectures with Spark, Iceberg, and AWS (processing 15M+ records)
- ⚡ **Real-Time Streaming** – Kafka + Spark pipelines handling 1000+ events/min with exactly-once semantics
- 🤖 **AI Data Pipelines** – RAG systems, vector databases, and LLM integrations (built one that vectorized 5M+ articles)
- 📊 **Data Modeling** – Star schemas, SCD Type 2 tracking, DBT transformations for analytics teams

I care about: **reliability**, **performance**, **cost optimization**, and **good documentation**.

---

## 🛠️ Tech Arsenal

### Core Data Engineering
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-3C8CE7?style=for-the-badge&logo=apache&logoColor=white)
![DBT](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazon-redshift&logoColor=white)

### Programming & AI
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## 🚀 Featured Projects

### 🏎️ [Formula 1 Data Lakehouse Pipeline](https://github.com/naveethzan/f1-datalakehouse-pipeline)
Production-grade batch processing pipeline with Apache Spark, Iceberg, and AWS

**What it does:** Processes 15M+ F1 records through a medallion architecture (Bronze → Silver → Gold), with dual Airflow DAGs for historical loads and weekly incremental updates.

**Tech:** Apache Spark • Iceberg • Airflow • AWS Glue • S3 • EMR • CloudWatch

**Cool stuff I implemented:**
- SCD Type 2 for tracking driver team changes over time
- Partition-aware updates with idempotent processing
- Query optimization: 20% improvement through broadcast joins, partition pruning, and AQE
- Data quality validation and lineage tracking

---

### 📈 [Real-Time Stock Market Streaming Pipeline](https://github.com/naveethzan/nasdaq-streaming-pipeline)
Near real-time streaming platform with Kafka, Spark Structured Streaming, and Redshift

**What it does:** Ingests stock market data, processes it in real-time with technical analysis (RSI, Bollinger Bands), and loads into a star schema warehouse.

**Tech:** Kafka • Spark Structured Streaming • AWS EMR • Redshift • DBT • Avro

**Cool stuff I implemented:**
- Watermarking for handling late-arriving events
- Avro Schema Registry for data contracts
- Anomaly detection using statistical methods
- Checkpointing and exactly-once processing semantics
- Dead letter queues for failed records

---

## 💼 Work Highlights

**Co-Founder / Data Engineer** @ Zutual (Jun 2025 - Present)
- Building data infrastructure for AI-powered life tracking app
- Real-time ingestion pipeline using LiveKit and Deepgram APIs
- LLM-powered transformation pipeline (LangChain + OpenAI) converting conversations to structured data

**Senior Software Engineer** @ Kovai.co (Jan 2024 - May 2025)
- Built RAG pipeline for Document360 that vectorized 5M+ articles using MongoDB Atlas Vector Search
- Redesigned payment processing pipeline → **80% reduction in failures, 15% revenue increase**
- Implemented idempotent transaction handling for complex subscription workflows

**Software Engineer** @ Kovai.co (Jun 2021 - Dec 2023)
- Built Azure streaming pipeline (Event Hubs + Stream Analytics + MongoDB) processing 1000+ events/min
- Optimized batch windows → **40% fewer write operations, $500/month cost savings**
- **Received Technical Excellence Award (MVP Category)**

---

## 🎓 Education

**B.Tech in Information Technology** | Kumaraguru College of Technology, Coimbatore  
CGPA: 8.7/10 | Graduated 2021

---

---

## 📫 Let's Connect

Always happy to chat about data engineering, architecture patterns, or interesting projects!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/naveeth-za)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/naveethzan)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:naveethzan99@gmail.com)

---

<div align="center">
**"Good data engineering is invisible - until something breaks at 3 AM"** 🌙⚡

![Profile Views](https://komarev.com/ghpvc/?username=naveethzan&color=F85D7F&style=for-the-badge)

</div>
