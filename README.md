### Data Analysis Solar Emissions VS Emissions

## Motivation
Identify the impact of renewable energies and determine whether certain regions of the United States with better air quality have higher renewable energy usage.

## Questions for Data

1. Does renewable energy reduce air pollution?
2. Does solar energy reduce air pollution?
3. Is there a difference in states production and consumption of solar energy and how they impact air quality?
4. How important is population size to air quality? Does it have a greater impact than renewable energy?

## Data Cleanup and Exploration

**Census API** Population data
**NREL API** Emissions data
**EIA API** Solar Production, Solar Consumption, Total Renewable Energy Production and Consumption

## Data Analysis
Started with all states for initial correlation analysis from 2008-2017
Scaled it down to the 5 states with the largest change in emissions over the 10 year period

**Positive change:** OH, PA, IN, GA, IL\
**Negative change:** TX, WA, MS, ND, ID\
**No change:** VT\
**Highest population:** CA, FL, TX, NY, IL\
**Highest avg emissions:** CA, FL, TX, LA, PA

## Solar Production VS Air Quality
**Hypothesis:** If production of solar energy is related to air quality then increased solar production will lower CO2 emissions.
**Conclusion:** Reject the hypothesis. There is no correlation between solar production and lower CO2 emissions.
When looking at 5 states of interest there is a correlation showing states with higher solar production actually have higher emissions.

## Solar Consumption VS Air Quality
**Hypothesis:** States that consume more solar energy will have lower emissions. When looking at all 50 states there is no correlation between solar consumption and emissions.\
We received an r2 value of 0.1359

When looking at 5 states of interest there is a correlation showing states with higher solar consumption actually have higher emissions.\
We received an r2 value of 0.9200 for this data

## All Renewable Energies VS Air Quality
After seeing no strong correlation between solar energy and emissions levels, we expanded our search to examine renewable energy overall. 
This data represents Total Renewable Energy Metrics that include Biomass Energy, Geothermal Energy, Hydropower, Solar Energy, and Wind Energy. 

**Hypothesis:** That States that produce or consume more total renewable energy will have lower CO2 Emissions
**Conclusion:** The overall data shows that the level of state production or consumption of renewable energy compared to emissions is unrelated. 
It is worth noting, however that states with higher percentages of renewable energy consumption have lower CO2 emissions levels.

Our linear regression models show little if any correlation between renewable energy production and emissions levels. The same test seems to show no correlation between consumption percentage and emissions but if we take a closer look, we can see a trend formulating. \
r2 value = 0.2718592537766137\
pvalue = 6.79306335646375e-37

## Population VS Air Quality

**Hypothesis:** The higher the population, the lower the air quality.

After we spent some time comparing our previous data and observed multiple instances without a correlation. We were curious to find a factor that *did* impact emission rates.

So we decided to compare each states population to their total emissions over the course of 10 years.

We found that Texas completely skewed the averages as it's production rates were the highest despite not having the highest population in the U.S.A

**Conclusion:** There is definitely a correlation. To emphasize the trend, I narrowed my data down to just the five largest population states and compared their 10 year emissions totals to see if the trend was consistent, and it was.\
r-squared is: 0.6770672256936486

## Summary
Nationwide total emissions is decreasing.

There was no correlation in the factors we researched.

Something is impacting emissions rates but it is not necessarily solar production/consumption/renewable energies.

More research is needed but that was out of the scope of our project. 




