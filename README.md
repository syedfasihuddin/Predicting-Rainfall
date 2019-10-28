# Rainfall-Prediction-Austin

- - - -

##### Introduction: 

Rainfalls prediction is still a region that needs more research to make better arrangements and information for the people and organizations that have to deal with it. Based on our personal analysis we think that this analysis will help in better understanding of the rain based on the past events and if taken to a higher level it can also help people to understand the pattern of rainfalls and events corelated to it. This project will also help us in learning about how to process data and create useful prediction from it.

##### Goals:

Our goal in this project is to analyze the data and create a model from it that will help us in understanding weather behaviors for rainfall based on temperatures, precipitation, humidity and sea level pressures. This model will not only help us in predicting rainfall but it will also help in with the levels of rain fall like, drizzle, moderate rain and heavy rain. We will also cover and examine the events that occurred due to the rain or with it like, thunderstorm, fog and snow.

Our goals include.

* Creating a model to tie all links that are responsible for rain like humidity, precipitation level, temperatures, dewpoint and sea level pressure to predict levels of rains.

* To provide a better visual representation of the outcomes of this analysis through the prediction model by using seaborn and Heat-maps (Sea born to analyze the independent links like precipitation, humidity, temperature and sea pressure and to analyze the level of rains (like drizzle, moderate rain and heavy rain) we will use heat maps.

##### Source of Data and Background:

This dataset was obtained from WeatherUnderground.com and it was released by Austin KATT Station, the person who contributed this dataset on Kaggle is GrubenM. The format of the file that contains complete data is .csv This dataset contains data for every date from 2013-12-21 to 2017-07-31. This dataset contains temperatures, humidity, sea pressures, precipitation, rain levels, visibility and dewpoint for every day between above mentioned dates. The reason for releasing this dataset over the web is that people can have better understanding and explanation on variation of the rain. This dataset have total 21 entities (Columns) and 1319 values (Rows), The entities explaining the link are:

Date (YYYY-MM-DD) TempHighF (High temperature, in Fahrenheit) TempAvgF (Average temperature, in Fahrenheit) TempLowF (Low temperature, in Fahrenheit) DewPointHighF (High dew point, in Fahrenheit) DewPointAvgF (Average dew point, in Fahrenheit) DewPointLowF (Low dew point, in Fahrenheit) HumidityHighPercent (High humidity, as a percentage) HumidityAvgPercent (Average humidity, as a percentage) HumidityLowPercent (Low humidity, as a percentage) SeaLevelPressureHighInches (High sea level pressure, in inches) SeaLevelPressureAvgInches (Average sea level pressure, in inches) SeaLevelPressureLowInches (Low sea level pressure, in inches) VisibilityHighMiles (High visibility, in miles) VisibilityAvgMiles (Average visibility, in miles) VisibilityLowMiles (Low visibility, in miles) WindHighMPH (High wind speed, in miles per hour) WindAvgMPH (Average wind speed, in miles per hour) WindGustMPH (Highest wind speed gust, in miles per hour) PrecipitationSumInches (Total precipitation, in inches) ('T' if Trace) Events (Adverse weather events. ' ' if None)

##### Techniques:

* Linear Regression

* Logistic Regression

After initial analysis of data, we think that applying logistic regression and linear regression will help us to create a better prediction model, we will try to apply linear and logistic regressions independently on the data and then compare the outcomes and predictions of these two techniques together to have better understanding of the relation between two outcomes.

For visual representation we are planning to use scatter plots, seaborn charts and heat map to have a good pictorial representation, like for rain intensity we might use heat map and to co-relate precipitation levels with rain we will use scatter plots and to represent remaining entities links we will use seaborn charts.

##### Project Plan:

* Week 10 Complete Data Cleaning and Manipulation.

* Week 11 Complete Model building with Linear and Logistic Regression.

* Week 12 Complete Visual representation and Run tests to evaluate model.