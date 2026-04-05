# Fabric Data Pipeline Orchestration (Automated ELT)

## 📌 Overview
This project demonstrates how to orchestrate multi-stage ELT workflows in **Microsoft Fabric** using:

- Fabric Pipelines
- Notebook activities
- Dependency chains
- Scheduling
- Delta Lake transformations

---

## 🏗 Pipeline Architecture

Notebook 1 (Bronze) → Notebook 2 (Silver) → Notebook 3 (Gold)

Each stage runs only after the previous one completes successfully.

---

## 📁 Project Structure
