# Automated Sales Performance Reporting System

## Overview
This project automates daily operational performance monitoring, providing:
- Daily performance briefings
- Exception-based alerts for underperforming regions
- Data quality validation checks

## Technologies Used
- Python (Pandas)
- SQL (SQLite)
- Apache Airflow
- HTML reporting

## Features
- ETL pipeline for operational data
- Key metrics calculation (fulfillment rate, return rate)
- Automated reporting
- Data quality validation
- Alerting for underperformance

## Setup Instructions
1. Clone this repository
2. Set up virtual environment
3. Install dependencies
4. Generate sample Data
5. Set up database
6. Start Airflow: 
   - `airflow db init`
   - `airflow webserver --port 8080`
   - `airflow scheduler`
7. Access the Airflow UI at http://localhost:8080