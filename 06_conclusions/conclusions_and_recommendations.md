# Conclusions and Recommendations

# 1. Project Objective

The objective of this project was to analyze historical Uber trip data from the 2024 and 2025 tourist seasons in Dubrovnik, Croatia, to identify patterns in ride activity, fare performance, and potential earning opportunities.

The analysis also examined the relationship between Uber trip performance and external factors, including weather conditions and cruise ship arrivals.

The ultimate goal was to translate these findings into data-driven recommendations for optimizing driving schedules, while acknowledging the limitations of the available data.

# 2. Key Findings

## 2.1 Ride Activity and Driving Hours

The analysis identified a clear pattern in recorded Uber ride activity, with the highest number of completed trips occurring at approximately 19:00.

Ride activity generally increased throughout the afternoon and peaked during the evening, suggesting that these periods represented important opportunities for completing Uber trips.

However, recorded ride frequency reflects the driver’s working patterns and does not independently measure overall transportation demand.

## 2.2 Early-Morning Fare Performance

The highest average fare per trip was observed at approximately 04:00, reaching around €29.

Based on the driver’s firsthand operational experience, this pattern is strongly associated with early-morning airport transfers and Uber’s dynamic pricing during periods of high demand relative to driver availability.

Although this explanation is supported by practical experience, historical flight data were unavailable to statistically validate the relationship.

## 2.3 Most Promising Driving Periods

Sunday between 00:00 and 03:59 recorded the highest average fare total per active day (€99.11).

Other promising periods included Wednesday between 04:00 and 07:59 (€97.80), Thursday between 16:00 and 19:59 (€74.30), and Saturday between 16:00 and 19:59 (€71.20).

These figures represent recorded Uber fares per active calendar day within each time block, rather than earnings from a standardized four-hour shift. The results should therefore be interpreted cautiously, particularly where observations are limited.

## 2.4 Weather Conditions

Trips completed during dry weather had an average fare of €14.15, compared with €12.99 during rainy conditions.

The observed difference suggests that rainfall was not associated with higher average trip fares in this dataset.

However, the relatively small number of rainy-weather trips and potential differences in trip characteristics limit the conclusions that can be drawn.

## 2.5 Cruise Ship Arrivals

Uber trips recorded within three hours following cruise ship arrivals had approximately 11% higher average fares (€15.33) compared with trips without recent cruise arrivals (€13.81).

However, the fare generated per hour of completed trip time was lower following cruise arrivals (€48.86 versus €51.18).

This finding highlights the importance of considering trip duration alongside fare values when evaluating driving efficiency.

## 2.6 Overall Business Insight

The analysis demonstrates that the highest number of rides, highest average trip fare, and highest fare efficiency do not necessarily occur during the same periods.

Therefore, optimizing Uber driving schedules requires evaluating multiple performance indicators rather than relying exclusively on ride frequency or average fare values.

# 3. Business Recommendations

## 3.1 Prioritize Late-Afternoon and Evening Driving

Late-afternoon and evening hours should be considered priority periods when planning Uber driving schedules.

Recorded ride activity increased throughout the afternoon and peaked at 19:00, while the 16:00–19:59 time block demonstrated promising fare performance on several days, particularly Thursday and Saturday.

Recommendation: Prioritize testing driving sessions between 16:00 and 20:00, especially on Thursdays and Saturdays, while monitoring actual online hours, completed trips, and net earnings.

## 3.2 Explore Early-Morning Airport Opportunities

Early-morning hours demonstrated some of the highest average Uber fares, particularly around 04:00.

Based on the driver’s operational experience, airport transfers and Uber’s dynamic pricing are important factors contributing to these patterns.

Recommendation: Consider targeted early-morning driving sessions aligned with airport flight schedules, particularly when flight activity is high and driver availability may be limited.

However, these periods should be tested further because the historical dataset contains relatively few early-morning trips.

## 3.3 Use Cruise Ship Schedules as Supplementary Information

Cruise ship arrivals were associated with higher average trip fares, but not with higher fare efficiency per hour of completed trip time.

Recommendation: Monitor cruise ship arrival schedules when planning driving sessions, but avoid assuming that a greater number of cruise arrivals automatically results in higher earnings.

Cruise information should be considered alongside time of day, trip duration, traffic conditions, and other operational factors.

## 3.4 Avoid Using Rainfall as a Standalone Driving Signal

The analysis did not identify higher average Uber fares during rainy conditions.

Recommendation: Do not prioritize driving sessions solely because rainfall is forecast. Weather information may still be useful when combined with other indicators, but the available data do not support treating rain as a reliable signal of higher fares.

## 3.5 Measure Actual Driving Profitability

The analysis demonstrates that higher average trip fares do not necessarily translate into higher time-adjusted fare efficiency.

Recommendation: Future performance tracking should include total online hours, waiting time, platform commissions, fuel expenses, and other operating costs.

Tracking trips completed through Uber, Bolt, and private transportation services would also provide a more complete picture of overall driver earnings.

These additional measurements would allow future analyses to move beyond fare-based indicators and evaluate actual net profitability.

# 4. Limitations and Future Improvements

## 4.1 Dataset Scope

This analysis is based on 1,334 completed Uber trips recorded during the 2024 and 2025 tourist seasons in Dubrovnik, Croatia.

The dataset represents the activity of a single driver and cannot be considered representative of the entire Uber market in Dubrovnik.

Furthermore, the analysis excludes trips completed through Bolt and private transportation services.

Consequently, the recorded fare values do not represent the driver’s total income across all transportation activities.

## 4.2 Missing Working Hours and Operating Costs

The dataset does not include complete information about the driver’s online working hours, waiting periods between trips, or time spent repositioning the vehicle.

Additionally, recorded fares do not account for platform commissions, fuel, vehicle maintenance, depreciation, or other operating expenses.

Therefore, the calculated performance indicators should not be interpreted as actual hourly earnings or net profitability.

Future analyses should incorporate working hours and operating costs to calculate more accurate profitability metrics.

## 4.3 Unavailable Historical Flight Data

Airport transportation plays an important role in Dubrovnik’s tourism-related transport activity.

Based on the driver’s firsthand operational experience, early-morning airport transfers and Uber’s dynamic pricing contribute to higher fares during certain overnight periods.

However, historical flight arrival and departure data could not be incorporated because suitable historical datasets required paid API access.

This limitation prevented statistical validation of the relationship between flight schedules and Uber fare performance.

Future research could integrate flight arrival and departure schedules, passenger volumes, and flight delays to evaluate airport-related transportation patterns more accurately.

## 4.4 Limited Observations During Certain Periods

Some driving periods, particularly overnight and early-morning hours, contain relatively few recorded trips and active days.

As a result, unusually high average fares or fare totals may reflect a small number of observations rather than consistently repeatable earning opportunities.

Future research should include additional observations across comparable dates and driving periods to improve the reliability of these findings.

## 4.5 External Factors and Causality

Although the analysis identified associations between Uber fare performance, weather conditions, and cruise ship arrivals, these relationships do not establish causality.

Other variables, including traffic congestion, trip distance, driver availability, tourism activity, and seasonal demand, may influence the observed patterns.

Future research could use statistical modelling to control for these factors and evaluate their relative importance.

## 4.6 Future Development

The project could be extended by incorporating:

* Historical airport flight schedules and passenger arrivals.
* Complete driving-session records, including online and idle time.
* Bolt and private transportation trip data.
* Platform commissions and vehicle operating expenses.
* Additional tourist seasons and larger datasets.
* Predictive models for estimating ride activity and fare performance.

These improvements would support more reliable scheduling recommendations and potentially enable the development of a data-driven decision-support system for drivers.

#5. Final Conclusion

This project demonstrated how historical Uber trip data can be combined with external datasets to identify patterns in ride activity, fare performance, and potential earning opportunities in Dubrovnik, Croatia.

Using Python, Pandas, and data visualisation techniques, the analysis examined 1,334 completed Uber trips from the 2024 and 2025 tourist seasons, alongside historical weather conditions and cruise ship arrival records.

The findings revealed that the periods with the highest ride frequency did not necessarily generate the highest average fares. Early-morning hours showed particularly high average trip fares, while late-afternoon and evening periods demonstrated strong recorded ride activity.

Cruise ship arrivals were associated with higher average fares, although this did not translate into greater fare efficiency per hour of completed trip time. Similarly, rainy conditions were not associated with higher average trip fares in the observed dataset.

The central business insight is that effective driving schedule optimization requires evaluating multiple factors simultaneously, rather than relying on ride volume or fare values alone.

While limitations such as missing flight schedules, incomplete working-hour records, and unavailable operating costs prevent definitive conclusions about actual profitability, the analysis provides a foundation for more informed driving decisions.

Ultimately, this project demonstrates an end-to-end data analytics workflow, from data cleaning and integration to exploratory analysis, visualisation, and actionable business recommendations.

Future development could extend this approach into a predictive decision-support system that helps drivers identify promising driving periods based on historical patterns and external conditions.