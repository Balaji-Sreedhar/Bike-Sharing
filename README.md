# Project Name
> Bike Sharing 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Bike Sharing Assignment

Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

Goal
-To identify the variables increasing the sales, e.g. month, season
-To create a linear model that quantitatively relates bike demands with variables such as season, weekdays, weekends, etc.
-To know the accuracy of the model, i.e. how well these variables can predict bike demand.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The equation of best fitted line is:
cnt= 0.246 * yr - 0.083 * holiday - 0.198 * Spring - 0.321 * Light rain_Light snow_Thunderstorm - 0.090 * Mist_Cloudy + 0.063 * 3 + 0.123 * 5 + 0.148 * 6 + 0.153 * 8 + 0.193 * 9 - 0.049 * Sunday + 0.126 * 7 + 0.116 * 10

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns
- import statsmodels.api as sm
- from sklearn.model_selection import train_test_split
- from sklearn.feature_selection import RFE
- from sklearn.linear_model import LinearRegression
- from sklearn.preprocessing import MinMaxScaler
- from sklearn.metrics import mean_squared_error
- from sklearn.metrics import r2_score
- from statsmodels.stats.outliers_influence import variance_inflation_factor
- %matplotlib inline
- import warnings 
- warnings.filterwarnings('ignore')

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@balaji-sreedhar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->