# Fabric Lakehouse Medallion Architecture (Bronze → Silver → Gold)

## 📌 Overview
This project implements a full **Medallion Architecture** in Microsoft Fabric using:

- Fabric Lakehouse
- Delta Lake
- PySpark
- SQL
- Fabric Pipelines

It demonstrates how to ingest raw data into Bronze, cleanse and standardise it in Silver, and model curated business-ready datasets in Gold.

---

## 🏗 Architecture



- **Bronze:** Raw ingestion (CSV/JSON/API extracts)
- **Silver:** Cleansing, deduplication, schema enforcement
- **Gold:** Fact/dimension modelling for analytics

---

## 📁 Project Structure
