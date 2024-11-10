# Overview

This project visualizes basketball game data, including team and player performance. Data is extracted from game summary PDFs, stored in a PostgreSQL database, and visualized through Power BI.

## Dependencies 

- Python 3
- pdfplumber: for extracting data from PDF's 
    - pip install pdfplumber
- pandas: for data manipulation and saving to csv
    - pip install pandas
- PostgreSQL: For storing the extracted data 
Power BI: For data Visualization 

## Data Pipeline

STEP 1: PDF to CSV, Extract game data from PDFs into CSV files.

Step 2: Database Storage: Import CSV files into PostgreSQL tables.

Step 3: Data Visualization: Use Power BI to create dashboards that provide insights into game and player performance.

## CSV Files and Database Tables

The data is organized into four CSV files, each corresponding to a PostgreSQL table:

1. Game Summary: General game details.

2. Team Statistics: Team-level stats.

3. Player Statistics: Player-level performance.

4. Play-by-Play: Detailed play events.

## Extraction Summary

The data is extracted from PDFs using Python (pdfplumber and pandas) and saved into CSV files. These CSVs are then imported into PostgreSQL for further analysis and visualization.





