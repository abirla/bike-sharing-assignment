# Bike Sharing Assignment (Linear Regression Assignment)
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes for a US company - BoomBikes
The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
   
In this assignment, we will use concepts of Multiple Linear Regression to build a model the demand for shared bikes with the available independent variables.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
They want to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Conclusions
- Visualizing the data suggests a linear regression model can fit in to understand the demand of the shared bikes
- Temperature, WeatherSituation (specifically Light Snow), Windspeed and Year 2019 has impacted the demand of shared bikes
- The R2 score has come up as 0.815 which is pretty good and adjusted R2 of the model is 83.8
- The model equation look like
y = 0.2839 + 0.5287 * temp - 0.1639 * hum - 0.1822 * windspeed - 0.0580 * spring + 0.0541 * summer + 0.0967 * winter + 0.2299 *YR_2019 - 0.0534 * July + 0.0785 * Sep - 0.0415 * Sun - 0.2394 * LightSnow - 0.0540 * Mist

## Technologies Used
- python - v 3.12.14
- numpy - v 1.26.4
- pandas - v 2.2.2
- seaborn - 0.13.2
- matplotlib - 3.8.4
- sklearn - 1.4.2
- statsmodels - 0.14.2

## Acknowledgements
Give credit here.
- This project was inspired by the course in Machine Learning and AI with Upgrad facilitated by IIIT Bangalore.

## Contact
Created by @abirla - feel free to contact!

