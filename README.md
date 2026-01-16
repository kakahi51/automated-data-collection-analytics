# Automated Data Collection & Analytics Pipeline

This repository demonstrates an automated data collection pipeline where
raw transactional data is captured via RFID devices and processed into
structured analytics-ready datasets.

## Project Scope
- Automated data ingestion (RFID → backend)
- Relational database design
- Data quality validation
- KPI-ready analytical queries

Hardware components are treated purely as data sources.
The main focus is on data reliability, structure, and analytics usability.

## Data Pipeline Overview
RFID Scan → API Endpoint → MySQL Database → Analytics Queries → Dashboard Logic

## Key Features
- Automated ingestion without manual input
- Normalized relational schema
- Data quality checks (missing data, duplicates, anomalies)
- KPI-focused analytics queries

## Example KPIs
- Daily scan volume
- Unique user activity
- Data completeness rate
- Anomaly detection (duplicate scans)

## Tech Stack
- Backend: PHP
- Database: MySQL
- Data Source: RFID (ESP8266)
- Analytics: SQL

## Notes
This project is designed to demonstrate data engineering and analytics thinking,
not hardware-level implementation.
