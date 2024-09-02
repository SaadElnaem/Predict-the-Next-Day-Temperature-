# Predict the Next Day Temperature
A machine learning model is used to predict the next day's temperature based on previous records of many variables.

## Objective:
To predict the next-day temperature according to the given conditions, a machine learning model (regression problem) is used. Note: It is NOT a time-series problem.

## Dataset Description:
The dataset is composed of several next-day forecast variables, maximum and minimum temperatures of present-day, and geographic auxiliary variables collected for a period of 5 years by the Korean Meteorological Service over Seoul, South Korea. The output variable is the next-day average temperature (NextDayAvTemp).

## Dataset Variables:
1. Station: Used weather station number.
2. Present_Tmax: Maximum air temperature between 0 and 21 h on the present day (°C).
3. Present_Tmin: Minimum air temperature between 0 and 21 h on the present day (°C).
4. NextDayPred_RHmin: Forecast of next-day minimum relative humidity (%).
5. NextDayPred _RHmax: Forecast of next-day maximum relative humidity (%)
6. NextDayPred _Tmax_lapse: Forecast of next-day maximum air temperature applied lapse rate (°C)
7. NextDayPred _Tmin_lapse: Forecast of next-day minimum air temperature applied lapse rate (°C)
8. NextDayPred _WS: Forecast of next-day average wind speed (m/s)
9. NextDayPred _LH: Forecast of next-day average latent heat flux (W/m2)
10. NextDayPred _CC1: Forecast of next-day 1st 6-hour split average cloud cover (0-5 h) (%).
11. NextDayPred _CC2: Forecast of next-day 2nd 6-hour split average cloud cover (6-11 h) (%).
12. NextDayPred _CC3: Forecast of next-day 3rd 6-hour split average cloud cover (12-17 h) (%).
13. NextDayPred _CC4: Forecast of next-day 4th 6-hour split average cloud cover (18-23 h) (%).
14. NextDayPred _PPT1: Forecast of next-day 1st 6-hour split average precipitation (0-5 h) (%).
15. NextDayPred _PPT2: Forecast of next-day 2nd 6-hour split average precipitation (6-11 h) (%).
16. NextDayPred _PPT3: Forecast of next-day 3rd 6-hour split average precipitation (12-17 h) (%).
17. NextDayPred _PPT4: Forecast of next-day 4th 6-hour split average precipitation (18-23 h) (%).
18. Lat: Latitude (°).
19. Lon: Longitude (°).
20. DEM: Elevation (m).
21. Slope: Slope (°).
22. Solar radiation: Daily incoming solar radiation (wh/m2).
23. NextDayAvTemp: The next-day average air temperature (°C).

## Files Description:
1. Temperature_Record.csv: Raw data from the stations.
2. Unseen_test.csv: raw data to test the model performance on unseen data.
3. Build Model_Test on unseen data.ipynb: the model building and it is performance results on the unseen data.
4. Predict_NextDay_Temp.joblib: saved trained model.


