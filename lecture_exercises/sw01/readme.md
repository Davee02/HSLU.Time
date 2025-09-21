# SW 01 Exercises Solutions

## Part 1: Reflect on the data generation process of 2-3 time series datasets

### Dataset 1: Swiss Transport Real-Time Data (opentransportdata.swiss)

Source: [SBB  actual journey data from opentransportdata.swiss](https://data.opentransportdata.swiss/dataset/istdaten)

Data Collection Process: 
- Time Interval: Daily data collection capturing journeys completed during each day
- Time Range: Continuous collection with historical archives available, starting from 2016 up to the present
- Collection Method: Real-time data from customer information systems, combining actual operational data with last received forecasts when real-time information is unavailable

Influencing Factors/Laws:
- Weather conditions, technical disruptions, maintenance schedules, passenger volume
- Infrastructure: Hub station complexities that create cascading delays
- Seasonal Patterns: Tourist seasons, commuter patterns, holiday schedules

Expected Patterns:
- Daily Cycles: Morning and evening rush hour peaks
- Weekly Patterns: More delays during weekdays
- Seasonal Trends: More weather-related delays in winter
- Peaks during holidays and special events

### Dataset 2: Household Energy Consumption (Kaggle)

Source: [Household Electric Power Consumption dataset on Kaggle](https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set)

Data Collection Process: 
- Time Interval: One-minute intervals with some missing days
- Time Range: December 2006 to November 2010 (47 months)
- Collection Method: Smart meter data collection from one household, measuring various electrical parameters (active/reactive power, voltage, current, sub-metering)

Influencing Factors/Laws:
- Environmental: Temperature, daylight hours, seasonal changes
- Economic: Energy prices, efficiency incentives, tariffs
- Technological: Appliance efficiency, home automation systems, renewable energy (for example solar panels with battery storage)

Expected Patterns:
- Daily Cycles: Morning and evening consumption peaks, nighttime lows
- Weekly Patterns: Different weekday vs. weekend usage profiles
- Seasonal Trends: Heating (wither) and cooling (summer) demands, increased lighting needs in winter, more outdoor activities in summer
- Long-term trends: Adoption of energy-efficient appliances, changes in household size or behavior