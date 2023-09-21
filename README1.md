# DevOps IaC Challenge: Data Warehouse and Data Pipeline

## Description

Building an ETL pipeline that extracts data from Amazon Web Services S3, stages them in Redshift Cluster, and transforms data into a set of dimensional tables for the analytics teams. The Redshift cluster is created and maintained using the Infrastructure as Code paradigm and policies.

## Directory Structure

├── README.md
├── dwh.cfg
├── run.sh
├── analysis
    └── Exploratory Data Analysis.ipynb
    └── Performance Measure.ipynb
├── modules
    └── create_database.py
    └── create_tables.py
    └── sql_queries.py
    └── etl.py
    └── __init__.py

## Running Intrusctions

There is a shell script in the root directory that will call upon the required python scripts. Just use the shell file to run the program, logging will aid you in every step of execution.

Run: sh run.sh
## Setup Instructions
Explain how to set up and run
## Usage
Provide instructions on how to us
## CI/CD Pipeline
Explain how your CI/CD pipeline works
## Airflow DAGs (if applicable)
Describe the Airf
## Data Loading
Explain
## Folder Structure
Provide a brief overview of your repository's folder structure and what each directory contains.
## Troubleshooting
Include troubleshooting tips or common issues users might encounter and how to resolve them.

## Contact Information
Provide contact i
# Acknowledgments
If
## Contributing
Include information on how others can c
## Links


