# PM2.5 Levels Does Not Matter For The Spread Of COVID-19
Author: Jiayin Ye

## Abstract

The COVID-19 pandemic causes millions of infected people and deaths, and it prompts serious recession and social disruption all over the world. This project attempts to investigate the association between the COVID-19 transmission level and PM2.5 levels during the Omicron crisis and whether the association is causal, using data from multiple resources and treating each country in each week as an observation with over 400 samples. A linear mixed model with weekly new cases per 100,000 persons as the response variable, PM2.5 levels with 1-week lag as key predictor controlling for other environmental, vaccination-related, policy-related, demographic, and socioeconomic confounding factors, are employed to examine the effects of PM2.5 levels on the COVID-19 transmission level. The results consistently indicated that there is no significant association between PM2.5 levels and the COVID-19 transmission level during the Omicron crisis. And we can not state that the relationship is causal. Based on the findings, we should not consider PM2.5 as a very important determinant of the spread of the COVID-19.

## Data Sources

(1) the data set contains daily cases and deaths by date during the Omicron crisis from [the World Health Organization (WHO)](https://covid19.who.int/WHO-COVID-19-global-data.csv) website,

(2) the air quality data from [The World Air Quality Index project](https://aqicn.org/data-platform/covid19/) during COVID-19 pandemic, including air pollutant species (PM2.5, PM10, Ozone, etc., which are all converted to the US EPA standard) as well as meteorological data (Wind, Temperature, etc.), 

(3) the data set containing potential confounding factors, such as vaccine rate, population density, age distribution, from [Our World in Data](https://ourworldindata.org/coronavirus).
