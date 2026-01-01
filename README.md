# Hospital Bed Management Analysis (SQL + Python)
This project analyses hospital bed utilisation, patient demand, and service pressure using a SQL-based analytics workflow built in Python.

## Overview
- Dataset: Hospital Beds Management Dataset (Kaggle)
- Goal: Identify capacity pressure, refusal rates, and service bottlenecks across hospital departments
- Approach: Load raw CSV data into a relational database and perform analytical SQL queries

## Workflow
1. Downloaded and extracted multi-table hospital data using KaggleHub  
2. Loaded CSV files into a SQLite database using pandas and sqlite3  
3. Executed SQL queries to analyse:
   - Patient demand by service
   - Bed utilisation (bed pressure)
   - Patient refusal rates
   - Impact of events (e.g. flu, strikes) on hospital capacity
4. Calculated operational metrics directly within SQL for clarity and reproducibility

## Key Metrics
- **Bed Pressure** = patients_admitted / available_beds  
- **Refusal Rate** = patients_refused / patients_request  

These metrics highlight service-level capacity strain and access issues.

## Example Insights
- Emergency services consistently show the highest bed pressure and refusal rates  
- Flu events significantly increase refusal rates across all services  
- Emergency and General Medicine are most affected during high-demand periods  

## Tools & Technologies
- Python
- pandas
- SQLite
- SQL
- KaggleHub
- Jupyter / Google Colab

## Project Focus
This project emphasises:
- Structured data pipelines
- Relational data modelling
- SQL-based analytical reasoning
- Healthcare operations and decision support

## Future Improvements
- Visual dashboards (Power BI or Tableau)
- Time-series trend analysis
- Integration with staffing or resource allocation models
