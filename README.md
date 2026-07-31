# Uber Driver Demand and Earnings Analysis 
# Project Overview
This project analyzes my own Uber driver trip history completed in Dubrovnik, Croatia, during the 2024 and 2025 tourist seasons.
The objective is to identify the most profitable driving hours by analyzing ride demand and earnings while incorporating external factors such as weather conditions, cruise ship arrivals and flight schedules.
---
## Project Objectives
- Clean and prepare Uber driver trip data for analysis.
- Collect and integrate external datasets.
- Explore ride demand and earnings patterns.
- Identify the most profitable driving hours.
- Investigate how external factors influence demand.
- Build a simple machine learning model to explore demand prediction.
---
## Dataset
The project is based on my own Uber driver trip history exported from the Uber Driver website.
The cleaned dataset contains approximately **1,300+ completed trips** after removing cancelled and incomplete rides.
External datasets include:
- Weather conditions
- Cruise ship arrivals
- Flight schedules
---

#Project Workflow
### 1. Data Collection 
The project combines multiple data sources:
- Personal Uber driver trip history exported from the Uber driver website.
- Weather data collected through a public weather API.
- Cruise ship arrival schedules extracted from publicaly available PDF documents.
**Planned data source**
-Flight schedules (not included due to limited access to historical flight data)
## 2. Data Cleaning
- Removed cancelled and incomplete trips
- Removed irrelevant columns
- Renamed variables
- Converted date and time formats
- Converted distance from miles to kilometers
- Converted trip duration from seconds to minutes
- Checked for missing values
- Checked for duplicate records
- Performed feature engineering by creating time-based features(hour of day, day of week and month)
## 3. Data Merging
- Combine Uber trip data with external datasets.
## 4. Exploratory Data Analysis (EDA)
- Ride demand analysis
- Earnings analysis
- Time-based analysis
- Weather impact
- Tourism impact
- External factor analysis
## 5. Data Visualisation
- Demand trends
- Earnings trends
- Time series
- Correlation analysis
- Business insights
## 6. Machine Learning (Future work)
- Explore predictive models for ride demand.
- Investigate demand forecasting and earnings optimization.
---
## Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub
---
## Repository Structure
'''
01_data_collection/
02_data_cleaning/
03_data_merging/
04_eda/
05_visualizations/
06_machine_learning/
'''

---
## Key Business Question
**When are the most profitable hours to drive Uber, and how do external variables such as weather, cruise ship arrivals and flight schedules influence ride demand and driver earnings?**
---
## Current Progress
- Completed: Data Collection
- In progress: Data Cleaning
- Planned: Data Merging
- Planned: Exploratory Data Analysis
- Planned: Data Visualizations
- Planned: Machine Leaning

