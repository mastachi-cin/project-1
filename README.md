# Wine Pricing Forecast
Statistical analysis to predict the price of wine applying multiple regression, based on different factors as points, longitude, altitude, elevation and price by country.

Locate on a heat map the provinces of the wineries and display the points and price of the bottles of wine.

## Description

1. Starter.ipynb

  * Run Starter.ipynb on Jupyter Notebook to explore the detail of the analysis.
  * Use the file winemag-data_first150k.csv as origin of data.

2. Google API´s

  * Use the Google Geocoding API https://maps.googleapis.com/maps/api/geocode/json to get the latitude and longitude of the wineries
  * Use the Google Elevation API https://maps.googleapis.com/maps/api/geocode/json to get the elevation of the wineries

## Visualization

### Summary statistics

![Summary statistics](Output/summary_statistics.png)

### Histogram for price

![Histogram](Output/Pricesunder100_Boxplot.png)

### Boxplot by country price

![Boxplot](Output/PriceperCountry.png)

### Linear regression Price VS Points (by country)

![Linear regression](Output/linear_regresssion.png)

### Linear regression Price VS Latitude, Longitude, Elevation

![Linear regression](Output/lin_reg_lat_lon.png)

### Regression models

![Regression models](Output/regression_models.png)

## Team members

1. Eduardo Garza
2. Cintia Mercado
3. Mariana Revilla
