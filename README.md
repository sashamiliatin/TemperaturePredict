# TemperaturePredict
## 1. Introduction
### The general scientific consensus is that the Earth is warming. Over the past century, the temperature has already climbed 1.02 °C (1.84 °F) .
### According to the Intergovernmental Panel on Climate Change’s (IPCC) latest report, the main driving force of global warming is the increase in concentration of carbon dioxide in the atmosphere .
### The vast majority of carbon dioxide recently added to the air is from burning fossil fuels, or because of humans .
### Increased CO2 concentration in the air causes increased temperature on the earth, which is known as the greenhouse effect, meaning the atmosphere will trap heat that is released by the sun .
### The consequences of global warming can be catastrophic: the ocean will become more acidic(loss of coral reefs and other underwater organisms) ,number of hurricanes will increase due to the warming ocean water,less ice in glaciers and the polar ice caps and more
## So climate change should be investigated to know how significant each factor is!!!
## In this repository:
### 1. data collection
### 2. cleaning data
### 3. EDA (visualisation)
### 4. testing algorithms
### 5. predict future temperature anomaly

# Data colaction
### crawling: temperature hissory from 'https://www.ncdc.noaa.gov/cag/global/time-series/globe/land_ocean/all/12/1880-2021'.
### API : temperature.csv,co2.csv,methane.csv,nitrous.csv from 'https://www.ncdc.noaa.gov/cag/'
### selenium : 'https://www.co2levels.org/','https://www.oxygenlevels.org/','https://www.n2olevels.org/','https://www.temperaturerecord.org/','https://www.methanelevels.org/'
# Cleaning data:
### removing unused columns and characters like °C , date repaired , join all data together , fix NaN values , and finally we have data from 2021-03 to 1000-01
# EDA (visualisation):
### scatrer ,interpolate_data , lmplot and heatmap corr plots
# testing algoritms
### our goal to predict future temp. anomaly so we need regression algorithms. we tested linear regression , SVR and RandomForestRegressor .
#  predict future temperature anomaly:
### using RandomForestRegressor predict 12 month future anomaly
