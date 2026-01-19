# Automated Data Collection & Analytics Pipeline

## Background
This project demonstrates an end-to-end automated data collection and analytics pipeline designed to transform raw transactional events into structured, analytics-ready datasets. The system focuses on data reliability, structure, and usability for operational analysis rather than hardware implementation.

## Problem Statement
Manual data recording and semi-automated systems often lead to delayed reporting, duplicated records, and unreliable operational metrics. This project addresses how automated ingestion and structured data modeling can improve data accuracy and enable consistent KPI monitoring.

## Project Scope
- Automated data ingestion from real-time sources
- Relational database design for transactional data
- Data quality validation and reconciliation
- KPI-ready analytical queries for operational monitoring

> Hardware components are treated strictly as data sources. The primary focus is on data engineering and analytics workflows.

## Data Pipeline Overview
RFID Scan Event  
→ API Endpoint  
→ MySQL Transactional Database  
→ Data Validation & Aggregation Queries  
→ Analytics & Dashboard Logic

## Key Features
- Fully automated data ingestion without manual input
- Normalized relational schema to reduce redundancy
- Data quality checks (missing records, duplicate scans, anomalies)
- KPI-oriented analytical queries for operational insights

## Example KPIs
- Daily scan volume
- Unique user activity
- Data completeness rate
- Duplicate scan anomaly rate

## Analytics Use Cases
- Monitoring system usage trends over time
- Identifying abnormal scan behavior
- Evaluating data reliability for downstream reporting
- Supporting operational decision-making with real-time metrics

## Tech Stack
- Backend: PHP
- Database: MySQL
- Data Source: RFID events (ESP8266)
- Analytics: SQL

## Notes
This project highlights data pipeline design, data validation logic, and analytics thinking. Hardware-level implementation details are intentionally minimized to emphasize data reliability and analytical usability.
