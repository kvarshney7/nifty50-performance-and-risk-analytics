# NIFTY 50 Equity Performance & Risk Analytics
Overview
An end-to-end data pipeline and interactive business intelligence dashboard designed to analyze equity performance and sectoral risk across the NIFTY 50 index. This project leverages Python for robust data extraction and feature engineering, alongside advanced Power BI DAX expressions for real-time financial diagnostics.

Core Technologies
Data Processing & Engineering: Python (Pandas, NumPy)

Visualization & BI: Power BI, Advanced DAX

Data Source: National Stock Exchange (NSE) Raw Equity Data

Key Features
Automated Data Pipeline: Extracted and cleaned raw equity data, engineering custom time-series features necessary for structural financial modeling.

Dynamic KPI Tracking: Real-time calculation of Market Capitalization, P/E ratios, and dividend yields with user-adjustable time horizons ranging from 5 days to 5 years.

Advanced Risk Diagnostics: Integrated user-adjustable Simple and Exponential Moving Averages (SMA/EMA), paired with 90-day historical evolution charts.

Sectoral Heatmaps: Interactive visual matrices designed to isolate and compare performance across varying market sectors.

Repository Structure
/data: Contains the cleaned NSE datasets (Note: Raw data excluded for size/compliance).

/scripts: Python notebooks detailing the EDA, data cleaning, and feature engineering processes.

/dashboard: The .pbix Power BI file containing the data model and visualizations.
