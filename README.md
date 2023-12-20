# COVID-19 Analysis in New York Counties

## Overview

This Jupyter notebook delves into COVID-19 data, focusing on confirmed cases and deaths in New York state's counties. Utilizing libraries like pandas and matplotlib, the notebook explores various insights and trends throughout the pandemic.

## Data Sources

- **time_series_covid19_confirmed_US.csv:** Contains confirmed COVID-19 cases data for US counties.
- **time_series_covid19_deaths_US.csv:** Provides COVID-19 death data for US counties.
- **covid_county_population_usafacts.csv:** Offers population data for US counties.

## Analysis Overview

1. **Data Loading and Cleaning:**
   - Both cases and deaths datasets are loaded, filtered for New York state, and indexed on county names. Unnecessary columns are dropped.

2. **County Comparisons:**
   - Confirmed cases and deaths are visualized over time for specific counties like Kings, Queens, New York, and Suffolk.

3. **Moving Averages:**
   - Rolling 7-day averages are calculated for both cases and deaths to smooth out daily fluctuations and reveal underlying trends.

4. **Per Capita Analysis:**
   - Cases and deaths are normalized by county population to account for population differences and provide fairer comparisons.

5. **Top Counties:**
   - Top 10 counties based on total cases and deaths per million inhabitants are identified and visualized.

6. **Further Exploration:**
   - Additional analyses can be performed, such as investigating daily case/death increases, comparing growth rates across counties, and analyzing correlations with potential influencing factors.

## Key Findings

- New York City counties (Kings, Queens, New York) generally had higher case and death counts compared to Suffolk County.
- Moving averages reveal periods of rising and falling cases/deaths over time.
- Normalizing by population shows a more balanced picture, with some suburban counties having higher infection and death rates per capita.

## Visualizations

- Line charts showcasing:
  - Total confirmed cases and deaths in selected counties.
  - Rolling 7-day averages of cases and deaths in selected counties.
  - Top 10 counties with highest total cases and deaths per million inhabitants (normalized by population).

## Code Structure

- The code imports necessary libraries.
- It loads and cleans the cases, deaths, and population datasets.
- Specific counties are selected for analysis.
- Confirmed cases and deaths are visualized over time for the chosen counties.
- Rolling 7-day averages are calculated and plotted.
- Data is normalized by population and visualized for top 10 counties based on both metrics.


# 

## 

* 
* 
