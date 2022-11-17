# Income Price Prediction Project

This project was worked on as part of a requirement for my Master's Data Science Program at Bellevue University.

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project was to work with a raw data set and peform machine learning to train a predictive analytics model.

### Methods Used
* Machine Learning (Linear Regression, Logistic Regression)
* Data Visualization
* Summary Statistics

### Technologies Used
* Python (Pandas, NumPy, Matplotlib, Statsmodels,etc)
* SQL
* Jupyter

## Project Description
The first step in this project was collecting the data. The data was retrieved from Kaggle and imported into a Pandas dataframe. The dataset was a marketing dataset that contained a lot of interesting features such as income, education level, and the amount spend on different products. After the data was read in, there were some columns that needed to be cleaned. After the data munging stage, I used Matplotlib and Seaborn libraries to create visualizations to gain insights on underlying data trends. Once the data had been processed, two predictive models were trained. The first was a simple linear regression model using Statsmodel's OLS. The model was trained on the features and then used to predict the `income` column. The second model that was trained was a logisitic regression model. There were a few columns that measured whether a few targeted ad campaigns were successful. The logitic model was trained to predict whether the final ad campaign would be sucessful on future customers.
