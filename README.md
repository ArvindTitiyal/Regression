# Regression

Bike sharing systems are a means of renting bicycles where the process of
obtaining membership, rental, and bike return is automated via a network of
kiosk locations throughout a city. Using these systems, people are able to
rent a bike from one location and return it to a different place on an
as-needed basis. Currently, there are over 500 bike-sharing programs
around the world.
The data generated by these systems makes them attractive for
researchers because the duration of travel, departure location, arrival
location, and time elapsed is explicitly recorded. Bike sharing systems
therefore function as a sensor network, which can be used for studying
mobility in a city.

## Problem Statement
In this project, you are asked to combine historical usage patterns with
weather data in order to forecast hourly bike rental demand.
Data
You are provided with following files:
1. train.csv : Use this dataset to train the model. This file contains all the
weather related features as well as the target variable “count”. Train
dataset is comprised of first 18 months.

2. test.csv : Use the trained model to predict the count of total rentals for
each hour during the next 6 months.


## How good are your predictions?
Evaluation Metric
The Evaluation metric for this project is Root Mean Squared Logarithmic
Error (RMSLE). The RMSLE is calculated as:
Where:<br />
● n is the number of hours in the test set.<br />
● pi is your predicted count.<br />
● ai is the actual count.<br />
● log(x) is the natural logarithm.<br />

## Solution Checker
You can use solution_checker.xlsx to generate score (RMSLE) of your
predictions.
This is an excel sheet where you are provided with the timestamp and you
have to submit your predictions in the count column. Below are the steps to
submit your predictions and generate score:<br />
a. Save the predictions on test.csv file in a new csv file.<br />
b. Open the generated csv file, copy the predictions and paste them in the
count column of solution_checker.xlsx file.<br />
c. Your score will be generated automatically and will be shown in Your
Score column<br />

You can also check out the baseline Python Notebook provided to get
started.
