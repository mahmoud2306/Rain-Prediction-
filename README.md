# Rainfall Prediction Project

## Overview
This project aims to predict whether there will be rainfall the following day using various classification algorithms.The models are trained on historical weather data and evaluated using multiple performance metrics.

## Project Description
In this notebook, different classification algorithms were implemented to predict whether there will be rain the following day. The algorithms were trained on the training data and evaluated on the testing data using various evaluation metrics. Finally, the models were used to generate a report at the end.

## Dataset
The original source of the data is the Australian Government's Bureau of Meteorology, and the latest data can be gathered from [Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/). The dataset used in this project was gathered from the Rattle at [Rattle WeatherAUS Dataset](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData).

This dataset contains observations of weather metrics for each day from 2008 to 2017. The `weatherAUS.csv` dataset includes the following fields:

| Field         | Description                                                                 | Unit            | Type   |
| ------------- | --------------------------------------------------------------------------- | --------------- | ------ |
| Date          | Date of the Observation in YYYY-MM-DD                                       | Date            | object |
| Location      | Location of the Observation                                                 | Location        | object |
| MinTemp       | Minimum temperature                                                         | Celsius         | float  |
| MaxTemp       | Maximum temperature                                                         | Celsius         | float  |
| Rainfall      | Amount of rainfall                                                          | Millimeters     | float  |
| Evaporation   | Amount of evaporation                                                       | Millimeters     | float  |
| Sunshine      | Amount of bright sunshine                                                   | hours           | float  |
| WindGustDir   | Direction of the strongest gust                                             | Compass Points  | object |
| WindGustSpeed | Speed of the strongest gust                                                 | Kilometers/Hour | float  |
| WindDir9am    | Wind direction averaged of 10 minutes prior to 9am                          | Compass Points  | object |
| WindDir3pm    | Wind direction averaged of 10 minutes prior to 3pm                          | Compass Points  | object |
| WindSpeed9am  | Wind speed averaged of 10 minutes prior to 9am                              | Kilometers/Hour | float  |
| WindSpeed3pm  | Wind speed averaged of 10 minutes prior to 3pm                              | Kilometers/Hour | float  |
| Humidity9am   | Humidity at 9am                                                             | Percent         | float  |
| Humidity3pm   | Humidity at 3pm                                                             | Percent         | float  |
| Pressure9am   | Atmospheric pressure reduced to mean sea level at 9am                       | Hectopascal     | float  |
| Pressure3pm   | Atmospheric pressure reduced to mean sea level at 3pm                       | Hectopascal     | float  |
| Cloud9am      | Fraction of the sky obscured by cloud at 9am                                | Eights          | float  |
| Cloud3pm      | Fraction of the sky obscured by cloud at 3pm                                | Eights          | float  |
| Temp9am       | Temperature at 9am                                                          | Celsius         | float  |
| Temp3pm       | Temperature at 3pm                                                          | Celsius         | float  |
| RainToday     | If there was rain today                                                     | Yes/No          | object |
| RainTomorrow  | If there is rain tomorrow                                                   | Yes/No          | object |

