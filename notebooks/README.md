# Notebooks and scripts

This folder contains the project analysis artifacts for the MIT 805 assignment.

## Part 1
- `MIT805_Part1_HVFHV_EDA.ipynb` — exploratory analysis of the June 2026 HVFHV sample
- `MIT805_Part1_HVFHV_EDA_sql.ipynb` — SQL-based exploratory analysis using DuckDB/JupySQL

## Part 2
- `MIT805_Part2_HVFHV_PySpark.py` — scaffold for distributed Spark processing using the full HVFHV dataset

The Part 2 script is intentionally lightweight: it configures a local Spark session, loads the full public HVFHV parquet corpus, and includes two example PySpark queries using the real data. It is not a full EDA.

