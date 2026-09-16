venkata, I see exactly what’s happening — your **Repository Structure** section is not inside a code block, so GitHub is treating the tree characters (`│`, `├──`, `└──`) as normal text.  
That’s why everything is collapsing and appearing **side‑by‑side**, exactly like in your screenshot.

Let me fix your README **using your exact content**, with the correct code block applied.

Below is your README with the **proper fenced block** added ONLY to the Repository Structure section.

---

```markdown
# 📘 Fundamentals of Data Engineering

A structured, comprehensive repository covering the core principles, lifecycle, architectures, and practical workflows of modern Data Engineering.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Data Engineering Lifecycle](#data-engineering-lifecycle)
- [Repository Structure](#repository-structure)
- [Key Concepts](#key-concepts)
- [Mini Projects](#mini-projects)
- [Who This Is For](#who-this-is-for)
- [Resources](#resources)
- [License](#license)

---

## 🧠 Overview
This repository provides a complete foundation for understanding how data is generated, ingested, stored, transformed, and served in modern data systems.  
It follows industry‑standard practices inspired by the *Fundamentals of Data Engineering* framework.

---

## 🔄 Data Engineering Lifecycle
The repository is organized around the five major lifecycle stages:

1. **Generation** — Source systems, event creation, operational databases  
2. **Ingestion** — Batch, streaming, CDC, messaging systems  
3. **Storage** — Databases, data lakes, warehouses, lakehouses  
4. **Transformation** — ETL/ELT, modeling, quality checks  
5. **Serving** — BI, analytics, ML, APIs

---

## 📂 Repository Structure

```text
fundamentals-of-data-engineering/
│
├── 01_foundations/
│   ├── data_engineering_described.md
│   ├── lifecycle_overview.md
│   └── architecture_principles.md
│
├── 02_lifecycle_in_depth/
│   ├── generation_source_systems.md
│   ├── ingestion_batch_streaming.md
│   ├── storage_systems.md
│   ├── orchestration.md
│   └── transformation_modeling.md
│
├── 03_security_privacy_future/
│   ├── security_privacy.md
│   └── future_of_data_engineering.md
│
├── mini_projects/
│   ├── batch_pipeline_example/
│   ├── streaming_pipeline_example/
│   └── data_modeling_exercise/
│
└── resources/
    ├── glossary.md
    ├── diagrams/
    └── references.md
```

---

## 🔑 Key Concepts
- Data modeling (ERD, star schema, normalization)
- ETL vs ELT workflows
- Batch vs streaming ingestion
- Data warehouses, lakes, lakehouses
- Orchestration (Airflow, Prefect, ADF)
- Big‑data tools (Spark, Kafka)
- Cloud data platforms (AWS, Azure, GCP)
- Data governance, quality, lineage
- Security & privacy in data systems

---

## 🛠 Mini Projects
- Batch ingestion pipeline (files → warehouse)
- Kafka streaming pipeline (real‑time events)
- Spark transformation job
- Data modeling exercise (warehouse schema)
- End‑to‑end ETL/ELT workflow

---

## 🎯 Who This Is For
- Aspiring Data Engineers  
- Data Analysts transitioning into engineering  
- ML Engineers needing strong data foundations  
- Students learning modern data systems  
- Professionals preparing for interviews or real‑world projects  

---

## 📁 Resources
- Glossary of DE terminology  
- Architecture diagrams  
- Reference links to tools, docs, and learning materials  

---

## 📄 License
MIT / Apache‑2.0 (choose based on your preference)

---
```
🔥 Build a full professional repository layout  

Just tell me.
