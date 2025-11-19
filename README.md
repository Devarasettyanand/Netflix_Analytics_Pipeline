# Netflix_Analytics_Pipeline
🎬 Netflix Analytics Pipeline — AWS S3 + Snowflake + dbt  A production-grade end-to-end data engineering project built using AWS, Snowflake, and dbt, designed to demonstrate real-world data ingestion, modeling, transformation, testing, and documentation workflows.

<img width="761" height="349" alt="Dbt1" src="https://github.com/user-attachments/assets/94d7db97-6d28-441c-9b92-76c2ab0d2a6a" />


🚀 Project Overview

This project simulates how a modern data team builds a cloud-native ELT pipeline:

Extract Netflix CSV data

Load into AWS S3

Ingest raw files into Snowflake

Transform & Model data using dbt

Test, Document, Deploy with dbt best practices

The final output is a clean, optimized data model ready for analytics and dashboards.

🏗️ Architecture
AWS S3  →  Snowflake Raw  →  Staging  →  Dev  →  Prod  →  dbt Models

⚙️ Tech Used

Tech Used:

AWS S3 — Ingestion & file management

Snowflake — Data warehouse (Raw, Stage, Dev, Prod layers)

dbt — Transformations, Tests, Snapshots, Documentation

Python (optional) — Utils & automation

Netflix Dataset — Source data

❄️ Snowflake Components

Warehouses optimized for cost

Databases: RAW, STAGING, DEV, PROD

File formats, stages, COPY INTO

Incremental models

Time Travel + Zero Copy Clone usage

Performance-tuned SQL transformations

🧱 dbt Components
Models

Raw → Staging → Dim → Fact

Incremental + materialized models

Jinja macros for reusable logic

Seeds

Metadata tables

Static configs

Sources

Source freshness checks

Documentation

Snapshots

SCD Type 2 for historical Netflix data

Tests

Unique, Not Null

Relationships

Custom macro-based tests (advanced)

Documentation

Auto-generated docs site

Lineage graph

Table descriptions

📊 Key Features

Real-world Snowflake optimization

Layered data modeling

dbt testing framework

Cost-aware warehouse design

Analytics-ready outputs

Clean folder structure for interviews

🧑‍🏫 Why This Project Matters

This repo showcases end-to-end real-world skills expected from a Snowflake/Cloud Data Engineer:

Cloud storage ingestion

Warehouse design

SQL transformations

dbt pipelines

Testing & CI/CD readiness

Performance tuning

Cost optimization

Perfect for:

FAANG/MAANG interviews

Portfolio building

Hands-on Snowflake/dbt learning

⭐ Special Thanks

Thanks to Darshil for guidance and review that helped shape this project into a real-world pipeline.
