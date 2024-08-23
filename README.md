Simple ELT Pipeline with DBT, Snowflake, and Airflow
---
This repository contains a simple ELT (Extract, Load, Transform) pipeline built using DBT (Data Build Tool), Snowflake, and Apache Airflow. The project demonstrates the integration of these tools to create a robust, scalable, and automated data pipeline.

# On this page

1. [Project Overview](#project-overview)
2. [Key Components](#key-components)
3. [Packages and Explanation](#packages-and-explanation)
4. [Use Cases](#use-cases)

---
## Project Overview
- **Data Extraction:** Simulates data extraction from a source system.
- **Data Loading:** Loads the extracted data into a Snowflake data warehouse.
- **Data Transformation:** Uses DBT to define and manage transformations, enabling clean, structured data for analysis.

---
## Key Components
- **DBT (Data Build Tool):** Manages data transformations and modeling within Snowflake. DBT enables version control and modular code, making transformations easier to develop, test, and maintain.
- **Snowflake:** Serves as the data warehouse where raw and transformed data are stored. Snowflake's scalability and performance ensure efficient data processing.
- **Apache Airflow:** Orchestrates the entire pipeline, managing task dependencies, scheduling, and monitoring. Airflow ensures that the ELT process runs smoothly and on time.

---
## Packages and Explanation

- **dbt-core**:
    - *dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.*

- **dbt-utils**:
    - *Utility functions for dbt projects. For this project I used the Utility functions to generate the surrogate key for the line items.*

- **astro**:
    - *Astro by Cosmo supports with the automatic generate of Airflow tasks based on DBT models. Supports direct deployment of dbt projects using the Astro CLI.*

---
## Use Cases
This project is ideal for those looking to: 
- Understand how to integrate DBT, Snowflake, and Airflow in a data pipeline.
- Learn the basics of building and managing an ELT pipeline.
- Experiment with modern data stack tools in a simple, easy-to-follow example.
