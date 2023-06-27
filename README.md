# Beijing-Air-Quality
This repository contains a machine learning project that focuses on applying regression techniques to analyze air quality dataset of Beijing. The project aims to predict air quality parameters, i.e., PM2.5 based on various features and provide insights into the factors affecting air pollution in the city.

## Dataset
The dataset used in this project is "Beijing Multi-Site Air-Quality Data" from the UCI Machine Learning Repository.This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017.

Link - https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data

## Methods
This project employs various regression algorithms to predict air quality parameters. The implemented methods include:

1. Linear Regression
2. Random Forest Regression
3. Gradient Boosting Regression
4. K Neighbors Regression
5. Decision Tree Regression

## Results

The models are trained on the training set and evaluated on the testing set using performance metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.

| Model | MAE | RMSE | R-squared |
| :--- | :---: | :---: | :---: |
| Linear Regression | 30.18 | 45.55 | 0.67 |
| Random Forest Regression | 18.66 | 30.36 | 0.85 |
| Gradient Boosting Regression | 25.59 | 40.21 | 0.74 |
| K Neighbors Regression | 24.59 | 40.04 | 0.75 |
| Decision Tree Regression | 25.94 | 44.60 | 0.69 |

After evaluating the performance of different algorithms, the `Random Forest Regression` model stood out, achieving the highest R-squared score among all the models.
