# Codeless-AI-ML-2022-Project

## Overview
The project is about weather prediction by using KNIME. We use a dataset for weather prediction which is authored by Jeffrey Heer on Github.

https://github.com/vega/vega/blob/main/docs/data/weather.csv?fbclid=IwAR3jcck1UiTNRfemAhCxDVhrsgub4HmvKmCvGehhFjpr9rG1ug8CRQ9IiMo

The main objective of this project is to find out which model was the most accurate. 

![overall one](img/overall.png)


## Tools
- KNIME

##Columns
- Location
- Date
- Precipitation
- Temp_max
- Temp_min
- Wind
- Weather

## Methods
Our dataset is in the .CSV format, we must use the CSV reader node to access it.

![csv reader](img/csv.png)

for the location column it come with string type. we change it into date.

![string date](img/stringtodate.png)

then we change date to ID.

![date id](img/rowid.png)

this node will show the data of location which have 2 location is seattle and newyork.

![location two](img/location.png)

![location barchart](img/barchartlocation.png)

and this node will show the average of wind. the average wind is 3.8

![wind average node](img/wind.png)

![wind box plot](img/boxplotwind.png)

and this node will show the average of precipitation. which is 1.8

![precipitation node](img/precipitation.png)

![precipitation box plot](img/boxplotprecipitation.png)


We specify the data to make it easier to analyze. we use row filter and column filter to select just one location (Newwork).....



