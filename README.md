# RiwiVentas — Sales Data Analysis

## Overview
Project for **loading, cleaning, and analyzing sales data** using Python and PostgreSQL.  
Includes ETL, data cleaning, normalization, and exploratory data analysis (EDA) with visualizations.

## Workflow (HUs)

1. **HU1 — Data Loading & PostgreSQL**  
   Load raw CSV sales data and create PostgreSQL tables (`sales`, `products`, `customers`).

2. **HU2 — Data Cleaning & Normalization**  
   Remove duplicates, fill missing values, standardize text, normalize types, and generate data quality reports.

3. **HU3 — Exploratory Data Analysis**  
   Calculate metrics, top products, monthly sales, and customer insights with graphs.

---

## Project Structure

notebooks/ # Jupyter notebooks: HU1, HU2, HU3
backups/ # CSV backups of sales, products, customers
reports/ # Data quality graphs and summary tables
README.md
requirements.txt # Python dependencies

yaml
Copiar código

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
Create PostgreSQL database Riwiventas.

Update DATABASE_URL in notebooks.

Outputs

Cleaned CSV: ventas_limpias.csv

Data quality summary: reporte_calidad_tabla.csv

Graphs: reporte_calidad_datos.png

PostgreSQL tables: sales_cleaned, products, customers

Author

Daniela MQ
Date: 28/11/2024

License

MIT License