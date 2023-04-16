# EDA-Capstone-Project-Bike-Sharing-Demand-Prediction-
apstone Project

Project tile - Seoul Bike Sharing Demand Prediction
Description:
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by Alma Better.

Problem statement:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
Dataset description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
Attribute Information:
•	Date : year-month-day
•	Rented Bike count - Count of bikes rented at each hour
•	Hour - Hour of the day
•	Temperature-Temperature in Celsius
•	Humidity - %
•	Windspeed - m/s
•	Visibility - 10m
•	Dew point temperature - Celsius
•	Solar radiation - MJ/m2
•	Rainfall - mm
•	Snowfall - cm
•	Seasons - Winter, Spring, Summer, Autumn
•	Holiday - Holiday/No holiday
•	Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
Project Flowchart:
1.	Initial preparations(Loading the dependencies and the data)
2.	EDA
3.	Clean-Up
o	Handling null values
o	Handling duplicate values
o	Removing Outliers
4.	Feature engineering
o	Feature encoding
o	Checking correlation for feature removal
o	Removing Multicollinearity
o	Obtaining correlation between dependent and independent variables
5.	Pre-processing of the data
o	Target feature conditioning
o	Creating train and test dataset
o	Feature Scaling
6.	Model implementation
o	Linear Regression
o	Ridge Regression
o	Lasso Regression
o	Random forest regression
7.	Model explainability
8.	Conclusion:
1.	EDA insights:
o	Most number of bikes are rented in the Summer season and the lowest in the winter season.
o	Over 96% of the bikes are rented on days that are considered as No Holiday.
o	Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.
o	Most number of bikes are rented when there is no snowfall or rainfall.
o	Majority of the bikes are rented for a humidity percentage range of 30 to 70.
o	The highest number of bike rentals have been done in the 18th hour, i.e. 6pm, and lowest in the 4th hour, i.e. 4am.
o	Most of the bike rentals have been made when there is high visibility.
2.	Results from ML models:
o	Random Forest Regression is the best performing model with an r2 score of 0.6645.
o	Lasso Regression (L1 regularization) is the worst performing model with an r2 score of 0.4264.
o	Actual v/s Prediction visualisation is done for all the 4 models.
o	All 4 models have been explained with the help of SHAP library.
o	Temperature and Hour are the two most important factors according to all the models.
3.	Challenges faced:
o	Removing Outliers.
o	Encoding the categorical columns.
o	Removing Multicollinearity from the dataset.
o	Choosing Model explainability technique.
