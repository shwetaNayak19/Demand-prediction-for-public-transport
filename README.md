# Demand-prediction-for-public-transport

Build a model that predicts the number of seats that Mobiticket can expect to sell for each ride, i.e. for a specific route on a specific date and time.

Tags: Data Science, Data Analysis, Machine Learning, Linear Regression,Random Forest.

![image](https://user-images.githubusercontent.com/105973170/190310316-40ffaf59-0be8-4e1d-b991-8298e36d24bf.png)

# Summary

# Introduction:-

Public transport is an effective tool to address multiple societal challenges, regarding mobility, sustainability and livability. In this report we are going to study how Mobiticket a ticket booking platform can expect a number of bookings on a particular day and time.To analyze data provided by Mobiticket  regarding bus ticket sales of 14 routes end in Nairobi and originate in towns to the North-West of Nairobi towards Lake Victoria. We are building a regression model to help Mobiticket to predict number of tickets can sell on each ride.

# Working Process:-

In this project We had presented my analysis of data and We had used various regression algorithm to predict number of tickets namely.

Linear Regression
Ridge and Lasso
Gradient Bossting
Random Forest
XGBoost

We followed step by step process for the project like data collection, data cleaning, EDA, Visualization, Model Training and Testing, Hyperparameter Tuning and Evaluation.


In the first step we collected data and explored data set to get a rough idea about data. In data wrangling process on raw data, formatted data type of columns and added some columns for our analysis.

In this data the target variable was not given so we calculated Target variable by grouping data by ride and counted number of tickets for each ride id.

# Process Involved During Analysis:-

In EDA we divided analysis into several part to get better idea about data we checked month and days wise travel patterns, at what time of day people travel most etc. We used bar plot to check travel patterns of traveller from cities, month wise, day wise, year wise and weekend wise. Pie Chart to check which type of vehicle is used mostly for transportation, checked relationship of vehicle type and target variable also check relationship of travel time with target variable with respect to vehicle type.

After that we perform feature engineering, in feature engineering we created some new feature form available features with the goal of simplifying and speeding up data transformation while also improving model performance.

After feature engineering we selected feature to use to train our model and encoded categorical variables as ML model works with numerical data to do computation. We used label encoding and one hot encoding.

# Conclusion:-

As data is ready, we trained different model to check their performances and performed hyperparameter tuning to improve their performances by GridsearchCV technique. Out of all the model XGboost models gives the best performance.

ML Models and Metrics

![image](https://user-images.githubusercontent.com/105973170/192091003-58de03aa-7062-4701-a592-4e156fd07b72.png)


