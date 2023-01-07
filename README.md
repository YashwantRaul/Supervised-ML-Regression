# Supervised-ML-Regression
Bike sharing demand prediction

Introdiction

Bike sharing system is an innovative transportation strategy that provides individuals with bikes for their common use on a short-term basis for a price or for free. Over the last few decades, there has been a significant increase in the popularity of bike-sharing systems all over the world. This is because it is an environmentally sustainable, convenient and economical way of improving urban mobility. In addition to this, this system also helps to promote healthier habits among its users and reduce fuel consumption.


🎯 goals of this project are:
Understand the trends in the data and identify key factors affecting the hourly demand for rental bikes.
Build an appropriate regression model to forecast the number of rental bikes required per hour to reduce waiting time.

Attribute Information

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - Humidity in the air in %

Windspeed - Speed of the wind in m/s

Visibility - Visibility in m, 10m

Dew point temperature - Dew point temperature in Celsius

Solar radiation - Energy radiated by Sun in MJ/m2

Rainfall - Amount of raining in mm

Snowfall - Amount of snowing in cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours


Steps

First I explore the data, cleaned and preprocessed the data and then I performed the exploratory data analysis to extract information, in which I identified certain trends, relationships, correlation and found out the features that had some impact on our dependent variable and plotted the graph to visualize the impact on dependent variable. I also encoded the categorical variables. 

I build the various machine learning algorithms on our split and standardized data. I tried different algorithms namely; Linear regression, Ridge Regression, Lasso Regression, Decision Tree, Random Forest and Gradient boosting algorithm. I did hyper parameter tuning and evaluated the performance of the model. 

Conclusion

Random forest Regressor and Gradient Boosting using gridsearchcv gives the highest R2 score of 89% and 90% respectively.
Feature Importance value for Random Forest and Gradient Boost are different.

We can use Random forest Regressor and Gradient Boosting gridsearchcv  for predicting bike rented columns on a daily basis.
