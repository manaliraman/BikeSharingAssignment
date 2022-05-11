# Bike Sharing Assignment
A bike-sharing system:
It is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Objective:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* Data understanding and performing data quality checks
* Exploratory data analysis for visualizing categorical and numerical variables
* Checking for multicollinearity using HeatMaps and PairPlots
* Data preparation like rescaling numerical features, converting categorical to dummy variables and train test split
* Model building using mix of automated (RFE) and manual approach for feature selection
* Performing a residual analysis and validating all the assumptions of Linear Regression
* Model evaluation and validation

## General Information
We want to understand the factors affecting the demand for these shared bikes in the market. We want to know:
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands

## Conclusions
As per the final Model, the top 5 predictor variables that influences the bike booking are:
- Temperature (temp) - with coefficient value of ‘0.5709’
- Weather Situation (weathersit_light_snow) - with coefficient value of ‘-0.2439’
- Year (yr) - with coefficient value of ‘0.2294’
- windspeed - with coefficient value of ‘-0.1861’
- hum - with coefficient value of ‘-0.1613’
SO IT IS RECOMMENDED TO GIVE THESE VARIABLES UTMOST IMPORTANCE WHILE PLANNING, TO ACHIEVE MAXIMUM BOOKING.
