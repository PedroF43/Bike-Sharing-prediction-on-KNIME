# Knime Workflow on Rental Bike Sharing Dataset

The objective of this workflow is to predict the amount of bike sharing users at a given time using decision trees and random forests. The dataset used for this analysis is the [Bike Sharing Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset) which contains hourly and daily counts of rental bikes between the years 2011 and 2012 in the Capital bike share system, along with corresponding weather and seasonal information.

## Dataset
This dataset contains the hourly and daily count of rental bikes between the years 2011 and 2012 in the Capital bike share system with the corresponding weather and seasonal information.

## Weather API
Since the training dataset consists mainly of weather information, a free weather API from [OpenWeatherMap](https://openweathermap.org/api) has been integrated into the workflow. This allows the model to obtain current weather data, allowing us for example to ask how many users we are going to have tomorrow at 3 pm.
