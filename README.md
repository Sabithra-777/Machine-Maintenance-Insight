# Machine Maintenance Insight — DS Sprint Use Case 25

## Overview
End-to-end educational data science project for machine maintenance insight.

## Data disclaimer
All data are synthetic and generated for demonstration. They are not real industrial records.

## Datasets
- machines.csv: machine type, age, installation date
- sensor.csv: timestamp, machine, vibration, temperature, current
- usage.csv: date, machine, runtime, load, cycles
- alarms.csv: machine, timestamp, alarm type
- maintenance.csv: service date, action, downtime, record period

## Workflow
Data generation, data cleaning, EDA, feature engineering, Random Forest classification, evaluation, machine-priority ranking, and Excel export.

## Target and limitations
The target represents a simulated urgent repair in a future 15-day window. Model metrics demonstrate the workflow on synthetic data only and are not real-world performance evidence. Validate using authorized real data and time-aware evaluation before operational use.

## Run
Open Machine_Maintenance_Insight.ipynb in Google Colab and run cells from top to bottom.
