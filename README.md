## Numerical Methods
Author: Andrew Kwon

## Description
This project trains and evaluates different prediction models for a regression task. Scope of the project is to balance runtime performance with model quality.

## Introduction
A used car sales service is developing an app to attract new customers where users can quickly find out the market value of their car. In this project, we will need to build the model that predicts the car values. The company is interested in the quality (evaluated on RMSE), speed of the prediction, and time required for model training.

## Dataset
We have access to historical data such as technical specifications, trim versions, and prices, which are further detailed in the file **car_data.csv**:

**Features**
- *DateCrawled*: date profile was downloaded from the database
- *VehicleType*: vehicle body type
- *RegistrationYear*: vehicle registration year
- *Gearbox*: gearbox type
- *Power*: engine power in horsepower
- *Model*: vehicle model
- *Mileage*: mileage (in kilometers)
- *RegistrationMonth*: vehicle registration month
- *FuelType*: fuel type
- *Brand*: vehicle brand
- *NotRepaired*: vehicle repaired or not
- *DateCreated*: date of profile creation
- *NumberOfPictures*: number of vehicle pictures
- *PostalCode*: postal code of profile user
- *LastSeen*: date of the last activity of the user

**Target**
- *Price*: price in euro

## Requirements
- pandas
- numpy
- time
- matplotlib.pyplot
- sklearn.ensemble
- sklearn.linear_model
- sklearn.metrics
- sklearn.model_selection
- lightgbm
- catboost
