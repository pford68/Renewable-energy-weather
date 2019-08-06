# Note
This repository was forked from https://github.com/hugorcf.  
This repo will remain unchanged from the original.


# Predicting wind and solar generation from weather data using Machine Learning

Wind and solar generation from weather data is predicted using a linear regression algorithm and a dataset containing energy production and weather information for Germany during 2016.

More information can be found in my [blog post](https://medium.com/hugo-ferreiras-blog/predicting-wind-and-solar-generation-from-weather-data-using-machine-learning-998d7db8415e).

## Data

The data used in this analysis come from Open Power System Data, a free-of-charge platform with data on installed generation capacity by country/technology, individual power plants (conventional and renewable), and time series data. It can be obtained from:

https://open-power-system-data.org/

The platform contains data for 37 European countries, but here only the data for Germany in 2016 is used. In particular, two datasets are used:
* Time series with load, wind and solar, prices in hourly resolution. 
* Weather data with wind speed, radiation, temperature and other measurements. Given the huge amount of data, the Open Power System Data platform provides a CSV file for the German dataset for 2016 and a script to download the data for other countries and years.
