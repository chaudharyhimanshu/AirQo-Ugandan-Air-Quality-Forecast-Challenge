# AirQo-Ugandan-Air-Quality-Forecast-Challenge
This was the competition hosted on zindi.africa. In this challange we were provided with the metrological data( temperature, precipetation,
atmospheric pressure, humidity, wind speed, wind direction) of 5 continuous days. The objective of this challenge was to accurately forecast air quality (as measured by PM2.5 µ/m3) for each hour of the coming 25 hours across five locations in Kampala, Uganda. Forecasts will be based on the past 5 days of hourly air quality measurements at each site.
There were hugh missing values in the dataset. I used fbphophet to fill the nan values in the time series.
