# bike-sharing system
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Table of Contents
Importing required Libraries
Load data set
Inspect the data shape and information about null and data types
Check if there is any null values in the given dataframe
Replacing the data column name for better understanding
Dropping the unwanted columns
Check data head again
One hot encoding
Chnage the values of season column to categorical type
Chnage the values of Month column to categorical type
Chnage the values of the weekday column to categorical type
Chnage the values of the weather column to categorical type
Data Preparation for Linear Regression
Split Data into training and test
Build a Model using RFE and Automated approach
Build Model
Model 1
Model 2
Model 3
Model 4
Inference
Other Findings
Residucal Analysis
Multi Colinearity
Linearity Check
Homoscedasticity
Actual vs Predicted data
Intrepretting the Model
Results
Conclusion


## General Information
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
Significant variables to predict the demand for shared bikes
holiday
temp
Humidity
Season (winter ,spring)
Months(July, September)
Weekday Sunday
weathersit( Light Snow, Mist + Cloudy)

## Technologies Used
python3.0
numpy
pandas
matplotlib
seaborn 
sklearn
statsmodels
warnings

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad


## Contact
Created by [@githubusername] - feel free to contact me!

Karan singh bisht
Upgrad
MLC44

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available.