# Luxury-Housing-Sales-Analysis

This repository implements a reproducible, production-oriented data pipeline for luxury housing analytics using Python (ETL and cleaning), a relational database (SQL) for storage and aggregation, and Power BI for reporting and dashboarding. The sample workflow is designed to comfortably scale to 100,000+ rows and follows engineering best practices for data quality, observability, and repeatability.

Goals

* Clean and standardize a complex housing dataset (1,00,000+ records).
* Transform and load data into a SQL database with a well-defined schema.
* Provide aggregation-ready tables for fast reporting.
* Build Power BI dashboards by connecting directly to the SQL database.
* Offer documentation and scripts.

Prerequisites

*Python 3.11
*A SQL database:
 MySQL 
*Power BI Desktop (for development) 

How to Reproduce / Run End-to-End

*Create and activate Python environment.
*Configure database and set DATABASE_URL env var.
*Place raw data in data/raw/.
*Run the ETL scripts in order or use scripts.
