# Air-Quality-Forecasting--Outlier-Detection-in-Multivariate-Time-Series-Data
This is a dataset that reports on the weather and the level of pollution each hour for five years at the US embassy in Beijing, China.

The data includes the date-time, the pollution called PM2.5 concentration, and the weather information including dew point, temperature, pressure, wind direction, wind speed and the cumulative number of hours of snow and rain. The complete feature list in the raw data is as follows:

    No: row number
    year: year of data in this row
    month: month of data in this row
    day: day of data in this row
    hour: hour of data in this row
    pm2.5: PM2.5 concentration
    DEWP: Dew Point
    TEMP: Temperature
    PRES: Pressure
    cbwd: Combined wind direction
    Iws: Cumulated wind speed
    Is: Cumulated hours of snow
    Ir: Cumulated hours of rain

We can use this data and frame a forecasting problem where, given the weather conditions and pollution for prior hours, we forecast the pollution at the next hour.

This dataset can be used to frame other forecasting problems.