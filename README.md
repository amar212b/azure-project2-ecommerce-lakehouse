[![Deploy and Run Ecommerce Lakehouse Pipeline (Bundles)](https://github.com/amar212b/azure-project2-ecommerce-lakehouse/actions/workflows/databricks.yml/badge.svg?branch=main)](https://github.com/amar212b/azure-project2-ecommerce-lakehouse/actions/workflows/databricks.yml)
[![Run Ecommerce Lakehouse Pipeline](https://github.com/amar212b/azure-project2-ecommerce-lakehouse/actions/workflows/run-databricks-job.yml/badge.svg?branch=main)](https://github.com/amar212b/azure-project2-ecommerce-lakehouse/actions/workflows/run-databricks-job.yml)
# Project 2: Ecommerce Lakehouse on Azure Databricks

## Overview
This project implements an end-to-end lakehouse architecture using
Azure Data Lake Gen2 and Azure Databricks.

The pipeline processes ecommerce transaction data through
Raw → Bronze → Silver → Gold layers using Delta Lake.

## Architecture
- Azure Data Lake Gen2
- Azure Databricks
- Delta Lake
- GitHub CI/CD

## Pipeline Flow
1. Raw → Bronze: Ingest CSV data
2. Bronze → Silver: Clean & validate data
3. Silver → Gold: Business aggregations

## Technologies Used
- PySpark
- Delta Lake
- Azure Databricks
- GitHub Actions

## CI/CD
Pipelines are triggered via GitHub Actions,
which run Databricks Jobs using parameterized notebooks.

## Author
Amardeep Singh
