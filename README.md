# Hi, I'm Sundar 👋

**Data Engineer** | I build pipelines where the data that comes out is actually trustworthy.

4+ years building ETL/ELT systems, data quality frameworks, and governed data platforms across **Microsoft Fabric**, **Azure**, and **AWS**. Currently exploring the data infrastructure layer of AI — RAG pipelines, vector stores, and LLM-ready data systems.

---

## What I build

| Layer | Tools |
|---|---|
| **Cloud Platforms** | Microsoft Fabric · Azure (Databricks, ADF, Synapse, ADLS Gen2) · AWS (S3, Glue, Redshift) |
| **ETL / Pipelines** | PySpark · Spark SQL · Informatica PowerCenter · IICS · dbt · Azure DevOps CI/CD |
| **Data Quality** | Custom DQ frameworks · Great Expectations · MD5 hash validation · SCD Type 1 & 2 |
| **Governance & MDM** | IBM InfoSphere IGC · Reltio MDM · Unity Catalog · Data Lineage · GDPR/PII masking |
| **AI + Data** | RAG pipelines · FAISS vector search · LangChain · LLM-ready data infrastructure |
| **Analytics** | Power BI · Tableau · T-SQL · DAX |

---

## Featured Projects

### 🔷 [Medallion DQ Framework](https://github.com/yourusername/medallion-dq-framework)
Mirror of the production DQ system I built for Rice University EDBI (15+ source systems, Microsoft Fabric)
- **27 automated checks** across Bronze, Silver, Dim, Fact, and SCD2 layers
- **33-column audit log** · 20,500 rows validated · 99.2/100 avg DQ score
- Diagnosed a millisecond race condition causing false-positive SCD2 breaks in PROD
- `Microsoft Fabric` `T-SQL` `SCD Type 2` `Medallion Architecture` `Python`

---

### 🔷 [MDM Customer DQ Pipeline](https://github.com/yourusername/mdm-dq-pipeline)
Pre-MDM ingestion validation — the layer that prevents bad data from reaching Reltio/Salesforce MDM
- **1,000,000** synthetic customer records · **15 DQ assertions** · golden record generation
- 74% clean records → validated layer · 26% quarantined → exceptions layer
- MD5 hash deduplication → **439,000 unique golden records**
- `Python` `Pandas` `MDM patterns` `Parquet` `Data Quality`

---

### 🔷 [RAG Enterprise Pipeline](https://github.com/yourusername/rag-enterprise-pipeline)
The data engineering layer under enterprise AI — structured data → vector index → NL queries
- 600 chunks · 1,000-dim FAISS index · 5 sample enterprise queries answered
- Swap TF-IDF for OpenAI embeddings with one line
- `Python` `FAISS` `RAG Architecture` `Vector Search` `LangChain patterns`

---

### 🔷 [COVID-19 Medallion Pipeline (Azure)](https://github.com/yourusername/covid-medallion-pipeline)
ADF + Databricks pipeline over 2M+ European public health records
- Bronze → Silver → Gold with DQ checks at every layer
- Delta Lake incremental loads · PySpark schema normalization
- `Azure Data Factory` `Databricks` `PySpark` `Delta Lake`

---

## Certifications

| Badge | Cert | Date |
|---|---|---|
| 🟠 | Databricks Certified Data Engineer Associate | Feb 2026 |
| 🔵 | Microsoft DP-900 Azure Data Fundamentals | Feb 2026 |
| 🟢 | Reltio MDM Suite (5 certs) — Foundations · Solution Architect · Technical Consultant · Data Flow | Sep 2025 |

---

## Currently building
- [ ] dbt + Snowflake transformation pipeline with automated quality assertions
- [ ] AWS version of the Medallion pipeline (S3 + Glue + Redshift)
- [ ] Production RAG pipeline with OpenAI embeddings + pgvector

---

## Let's connect

📍 St. Louis, MO · Open to full-time roles in Data Engineering, Data Quality, MDM, Governance, AI+Data
🔗 [LinkedIn](https://linkedin.com/in/sundarpalaniappan)
📧 vsvpl99@gmail.com

---

"I once traced a production failure to a millisecond-level race condition hiding in SCD2 timestamps. Nobody asked me to find it. That's the kind of engineer I am."
