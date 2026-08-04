# ✈️ SkyLink Global Airline Data Warehouse

> **End-to-end Data Warehouse solution for airline operations built with Azure and PostgreSQL, implementing ETL pipelines and a Medallion Architecture (Bronze, Silver, Gold) to support scalable data integration and business analytics.**

---

##  Project Overview

Modern airline operations generate large volumes of operational data from multiple sources, including flight plans, passenger reservations, baggage handling, cargo operations, maintenance records, aircraft positioning, fuel consumption, and engine sensor data. Managing this information efficiently requires a scalable architecture capable of integrating, transforming, and organizing data for analytical purposes.

This project presents the design and implementation of an end-to-end Data Warehouse for an airline environment. The solution follows the **Medallion Architecture**, organizing data into **Bronze**, **Silver**, and **Gold** layers to progressively improve data quality and prepare information for business analytics.

The project integrates multiple CSV datasets, catalog tables, and synthetic data generated to simulate real-world airline operations. Through ETL processes, raw data is validated, cleaned, standardized, enriched, and transformed into a dimensional model optimized for reporting and decision-making.

The final solution demonstrates the complete lifecycle of a modern data engineering project, from data ingestion and storage to transformation, integration, and analytical modeling.

---

##  Objectives

- Design and implement an end-to-end Data Warehouse for an airline environment.
- Apply the Medallion Architecture (Bronze, Silver, Gold) to organize the data lifecycle.
- Develop ETL pipelines to ingest, clean, transform, and integrate operational data.
- Import and standardize information from multiple CSV files and catalog tables.
- Generate synthetic datasets to simulate operational scenarios and complement missing information.
- Apply data enrichment techniques to improve data quality and analytical value.
- Build a dimensional model that supports business intelligence and reporting.

---

##  Technology Stack

| Category | Technologies |
|----------|--------------|
| Cloud | Azure |
| Database | PostgreSQL |
| Language | SQL |
| Architecture | Medallion Architecture |
| Data Processing | ETL |
| Data Sources | CSV Files, Catalog Tables, Synthetic Data |
| Version Control | Git & GitHub |

<img width="678" height="822" alt="arquitectura_solucion" src="https://github.com/user-attachments/assets/37ac4a74-279c-477c-b729-ae8539114de3" />
