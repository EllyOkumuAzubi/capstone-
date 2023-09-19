# capstone-
## TEAM PARIS CAPSTONE PROJECT CHURN-ANALYSIS 

## Summary
| Code      | Problem        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| TEAM PARIS | Churn Analysis |  https://huggingface.co/spaces/ellyothim/CapstoneChurnAnalysis (not yet working) |  https://github.com/EllyOkumuAzubi/capstone-|

## Project Summary Description
Our project is a time series regression analysis project, Where we build regression project and build various models . Afterwards we will select and deploy our best model after tuning. 

## Setup
The set up of the training set was divided into 4 parts 

Part 1 : Understanding the business Objective and defining the success 
     
Part 2 : Understanding our data 
    Here we had a series of formulated questions and hypothesis to better understand our data 


Part 3 : Prepare our data for training 
    (a) Encode the categorical column
    (b) Scale the data, to prevent over/under fitting 
    (c) Split the data into train set and test set 

Part 4 : Training our various ML models and evaluate their metrics 
    (a) Model 1 - Linear Regression 
    (b) Random Forest 
    (c) Support Vector 
    (d) X Boost 1
    (e) X Boost 2 
    (f) Arima Model

| Model | r_2score | mean squared error | mean average error |
|-------|----------|--------------------|--------------------|
| Linear Regression | 0.233980 | 9.520182e+05 | 421.559150 |
| Random Forest | 0.937429 | 7.776341e+04 | 54.922638 |
| Support Vector | 0.350954 | 8.066418e+05 | 386.584585 |
| X Boost 1 (n=10) | 0.772901 | 2.822418e+05 | 194.316372 |
| X Boost 1 (n=50) | 0.772901 | 2.822418e+05 | 194.316372 |
| AR | 0.699139 | 1.211640e+06 | 510.246890 |


Part 5 : Fine tune our model
The goal is to: 
-(a) minimize RMSLE
-(b) increase r2 score  




## App Execution
...

**Authors**

- Elly Okumu

- Awudu Jamal

- Jonas Afutu

- Vincent Kipkorir 

- Eric Mugisha

- David Mantey

