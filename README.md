# Bike Sharing Assignment
> Boom Bikes is a bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allows people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. Boom Bikes would like to predict the demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Business Objective
The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
### Technical Objective
To use Multiple Linear Regression to build a model to predict the key factors that affect the demand for bike rentals from the given dataset. The company wants to know:
  - Which variables are significant in predicting the demand for shared bikes?
  - How well do those variables describe the bike demands
### Steps Followed in Model Building
The major steps followed are:
- Reading and Understanding the Data
- Visualizing the Data
- Data Preparation
- Splitting the Data into Train and Test Sets
- Building a Linear Model
- Residual Analysis of the Trained Data (Assumption Evaluation)
- Making Predictions Using the Final Model
- Model Evaluation
- Equation of the Best-Fit Model
- Best-Fit Model Interpretation Based on the Equation

### What is the dataset that is being used?
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors in the form of a dataset: day.csv

## Libraries Used
#### Data manipulation
- numpy
- pandas
#### Data visualization
- matplotlib
- seaborn
#### Data analytics and modeling
- statsmodels
- sklearn
  
## Conclusions
- The given dataset has been split in the 70-30 ratio for training-test sets.
- The r-squared value of the model on the training data is 0.823 with an adjusted r-square score of 0.819.
- The r-squared value of the model on the test set is 0.796.
- The equation of the best-fit model is: 
  cnt = 0.070264 + 0.539040 x temp - 0.297362 x lightsnow + 0.231263 x yr + 0.146153 x winter + 0.123609 x sep - 0.100177 x holiday + 0.095578 x summer - 0.080930 x mist + 0.058455 x aug
- The top five significant variables in predicting the demand for shared bikes:
  - Temperature
  - Weather situation (light snow)
  - Year
  - Season (Winter)
  - month (September)

## Acknowledgements
The diagrams for `General Subjective Questions` have been taken from:
- https://www.geeksforgeeks.org/anscombes-quartet/
- https://www.statisticshowto.com/q-q-plots/

## Contact
Created by [@jenifer2409] - feel free to contact me!
