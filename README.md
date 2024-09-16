---

# BI Development & Analytics Project

## Project Overview
This project was part of a Business Intelligence Systems (BI) course that focused on applying BI methodologies and tools to analyze and visualize data. The project involves the design and implementation of a data warehouse, ETL processes, and the creation of dashboards for decision-making purposes.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [ETL Process](#etl-process)
- [Data Analysis & Visualization](#data-analysis--visualization)
- [Files in This Repository](#files-in-this-repository)
- [How to Use](#how-to-use)
- [Authors](#authors)

## Objectives
The main goals of this project were:
1. To analyze the business environment and define the data sources.
2. To design a data warehouse and implement an ETL process for data integration.
3. To develop a series of key performance indicators (KPIs) for business decision-making.
4. To create visual dashboards to support data-driven decisions.

## Methodology
The project was conducted in the following phases:
1. **Part A: Business Environment Analysis**  
   - **Business Process Analysis**: Understanding the organization's business processes and decision-making workflows.
   - **KPI Definition**: Developing KPIs to measure business performance.
   - **Data Source Identification**: Identifying and analyzing operational data sources, creating an ERD, and designing the primary database.
   - **Data Warehouse Design**: Creating a tabular model for the data warehouse.
   
2. **Part B: ETL Process and Advanced Data Integration**  
   - **ETL Process Design**: Developing ETL processes to mirror data, transform dimensions, and ensure referential integrity.
   - **Fact and Dimension Tables**: Creating tables to store and aggregate data in the warehouse.
   - **Advanced Applications**: Implementing advanced ETL techniques like handling slow-changing dimensions and using stored procedures.
   
3. **Part C: Data Analysis & Visualization**  
   - Using R for statistical analysis to identify correlations and trends in the data.
   - Building interactive dashboards in Tableau for data visualization.

## ETL Process
The ETL (Extract, Transform, Load) process involved several key steps:
1. **Data Mirroring**: Copying the original database to avoid data duplication.
2. **Dimension Staging**: Transforming dimensions to fit into the star schema model.
3. **Fact Staging**: Applying transformations to fact tables and aggregating data.
4. **Referential Integrity**: Ensuring data consistency between dimension and fact tables.
5. **Fact Warehousing**: Transferring data to the final warehouse tables for analysis.

## Data Analysis & Visualization
- **R Analysis**: Statistical analysis using R to explore relationships between variables (e.g., correlation between delivery choices and order amounts).
- **Tableau Dashboards**: Created dashboards to visualize key metrics like average income per order, customer satisfaction, and order fulfillment times.
  
## Files in This Repository
- **BI & Analytics Project.pdf**: Detailed project report covering the business analysis, ETL process, and data visualization.
- **BIS Syllabus.pdf**: Course syllabus providing context for the project.
- **Regression Part A+B.R**: R script used for data analysis and visualization.
- **Regression Part B - Finale.R**: Final R script for data processing.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/RoiAzrai/BI-Develop--and-Analytics-Project.git
    ```
2. Review the project report (PDF) for an in-depth understanding of the analysis, ETL process, and dashboard creation.
3. Open and run the R scripts to reproduce the analysis and data processing steps.

## Authors
- **Roi Azrai (Roi Ezrai)** - [LinkedIn](https://www.linkedin.com/in/roiazrai) | [GitHub](https://github.com/RoiAzrai)
- **Team Members**: Ron Beitan, Ori Ben-David

---
