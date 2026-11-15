# Uber Driver Analytics: Ride Patterns, Fare Performance & Driving Optimisation
# Project Overview
This project presents an end-to-end data analytics study based on 1,334 completed Uber trips recorded during the 2024 and 2025 tourist seasons in Dubrovnik, Croatia.

Using Python, Pandas, and Jupyter Notebook, I cleaned and integrated historical Uber trip records with weather data and cruise ship arrival schedules to investigate patterns in ride activity, fare performance, and potential earning opportunities.

The analysis explores how driving hours, days of the week, weather conditions, and tourism-related activity relate to recorded Uber fares.

The project includes data cleaning, data integration, exploratory data analysis (EDA), six final visualisations, and actionable business recommendations.

The main objective is to identify promising driving periods and demonstrate how data-driven insights can support more effective driving schedule decisions.

The analysis focuses exclusively on Uber trips. Recorded fares do not represent the driver’s total or net earnings, and historical flight schedules could not be incorporated due to limited access to suitable data.
---
## Project Objectives
* Clean and prepare historical Uber trip data for analysis.
* Integrate Uber trip records with historical weather and cruise ship arrival data.
* Analyse ride activity and fare performance across different hours, weekdays, and tourist seasons.
* Investigate relationships between external factors and Uber fare performance.
* Identify promising driving periods based on recorded fare patterns and trip activity.
* Translate analytical findings into actionable business recommendations.
* Demonstrate an end-to-end data analytics workflow using Python, Pandas, and data visualisation.
---
## Dataset

This project uses three datasets to investigate Uber ride activity and fare performance in Dubrovnik, Croatia, during the 2024 and 2025 tourist seasons.

1. Uber Trip Data

* 1,334 completed Uber trips from the driver’s personal trip history.
* Includes trip timestamps, distance, duration, ride category, and fare information.
* Cancelled and incomplete trips were excluded during data cleaning.

2. Historical Weather Data

* Hourly weather observations matched with Uber trip timestamps.
* Includes precipitation measurements and a binary indicator for rainy conditions.

3. Cruise Ship Arrival Data

* Historical cruise ship arrival schedules for Dubrovnik.
* Includes daily and hourly cruise arrival counts.
* Used to investigate fare patterns following cruise ship arrivals.

#### Data Limitations

Historical airport flight schedules were not included because suitable historical flight data required paid API access.

The dataset covers Uber trips only and excludes Bolt and private transportation services. Recorded fare values do not represent the driver’s total or net earnings.
---

# Project Workflow
Project Workflow

## 1. Data Collection

The project combines three data sources:

* Personal Uber trip history exported from the Uber Driver platform.
* Historical weather observations collected through a public weather API.
* Cruise ship arrival schedules extracted from publicly available PDF documents.

Historical flight schedules were considered but could not be included due to limited access to historical flight data.

## 2. Initial Data Inspection (Microsoft Excel)

Before beginning the data cleaning process in Python, I independently reviewed the raw Uber dataset in Microsoft Excel to understand its structure, identify potential data quality issues, and explore preliminary patterns.

### Key Initial Observation – Base Fare Reduction

During the initial inspection, I identified a reduction in Uber’s base fare from €1.79 in July–August 2024 to €1.48 in July–August 2025, representing an approximate 17.3% decrease.

This observation raised an important business question: whether changes in Uber’s base fare structure were associated with changes in overall trip values and potential earning opportunities.

It also helped guide the subsequent analysis of fare performance across the two tourist seasons.

## 3. Data Cleaning

* Removed cancelled and incomplete Uber trips.
* Removed irrelevant columns and renamed variables.
* Converted timestamps into appropriate datetime formats.
* Converted trip distances from miles to kilometres and durations from seconds to minutes.
* Checked for missing values and duplicate records.
* Created time-based features, including hour of day, weekday, month, and year.
* Cleaned and prepared historical weather and cruise ship arrival datasets.

## 4. Data Integration

* Integrated Uber trip records with hourly weather observations.
* Matched cruise ship arrival information to trip dates and hours.
* Created additional variables to examine cruise ship arrivals within the previous three hours.
* Produced an analysis-ready dataset containing 1,334 completed Uber trips.

## 5. Exploratory Data Analysis (EDA)

* Examined ride frequency, fare distributions, and trip characteristics.
* Analysed hourly, daily, and seasonal patterns.
* Compared average fares and recorded fare performance across different driving periods.
* Investigated associations between weather conditions, cruise ship arrivals, and Uber fares.
* Evaluated fare efficiency relative to completed trip duration.

## 6. Data Visualisation

Created six final visualisations illustrating:

* Uber ride activity by hour.
* Average Uber fare by hour.
* Fare performance by weekday and time block.
* Average fares under rainy and dry conditions.
* Fare patterns following cruise ship arrivals.
* Fare efficiency following cruise ship arrivals.

## 7. Conclusions and Business Recommendations

* Identified promising driving periods based on historical trip records.
* Examined the relationship between ride frequency and fare performance.
* Developed data-informed recommendations for driving schedule optimisation.
* Documented analytical limitations and opportunities for future research.

## 8. Future Development

Potential future improvements include integrating historical airport flight schedules, complete working-hour records, operating costs, and additional transportation platform data.

These extensions could support more accurate profitability analysis and the development of predictive models for driving schedule optimisation.

---
# Key Findings

The analysis of 1,334 completed Uber trips from the 2024 and 2025 tourist seasons revealed several important patterns.

## 1. Ride Activity and Peak Hours

Recorded Uber ride activity peaked at 19:00, with a noticeable increase in completed trips during the afternoon and evening.

However, recorded ride frequency reflects the driver’s activity and does not independently measure overall market demand.

## 2. Early-Morning Fare Performance

The highest average fare per trip occurred around 04:00, reaching approximately €29.

Based on firsthand driving experience, early-morning airport transfers and Uber’s dynamic pricing are important factors contributing to these patterns.

However, the relationship could not be statistically validated because historical flight data were unavailable.

## 3. Promising Driving Periods

The highest average recorded fare totals per active day were observed during:

* Sunday, 00:00–03:59: €99.11
* Wednesday, 04:00–07:59: €97.80
* Thursday, 16:00–19:59: €74.30
* Saturday, 16:00–19:59: €71.20

These figures represent average Uber fare totals on calendar days with recorded trips in each time block, not actual earnings from standardized four-hour shifts.

## 4. Weather Conditions

Average recorded fares were €14.15 during dry conditions, compared with €12.99 during rainy conditions.

Rainfall was not associated with higher average trip fares in the observed dataset.

## 5. Cruise Ship Arrivals

Trips recorded within three hours following cruise ship arrivals had approximately 11% higher average fares (€15.33 versus €13.81).

However, fare efficiency per hour of completed trip time was lower following cruise arrivals (€48.86 versus €51.18).

## 6. Main Business Insight

Higher ride frequency, higher average fares, and greater time-adjusted fare efficiency do not necessarily occur during the same periods.

Effective driving schedule optimisation therefore requires considering multiple performance indicators rather than focusing exclusively on ride volume or trip prices.
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

