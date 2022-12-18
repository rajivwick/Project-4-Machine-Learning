## Project-4-Machine-Learning
Concept of a restaurant informational dashboard using machine learning to provide predictions/forecasts from POS data and other sources (pytrends, etc)# Historical Analysis 

## Project Proposal - Machine Learning for forecasting and prediction - Restaurant Analysis

Please find the project proposal inside the folder marked Documents

### Project Title - Restaurant Dashboard - a litte bit of machine learning and a sprinkle of visual analysis

### Purpose of project 

Economic slow down means every business needs to stay intelligent about their decision making.
Small restaurants are at risk – Less general spending by consumers as well as increasing rent costs due to interest rate hikes are causing stress on owner. 
By using data and machine learning, can we optimizing aspect of a running business?


### Team Members  	

Rajiv Wickramaratne


## Sources of Data

-   POS data obtained from local family restaurant

-	https://www.indexmundi.com/commodities/?commodity=chicken&months=240&currency=aud#dropdown-lvl107
-	https://www.indexmundi.com/commodities/?commodity=lamb&months=240&currency=aud
-	https://www.indexmundi.com/commodities/?commodity=beef&months=240&currency=aud


## Application

### NOTE

In order to run the app, once locally stored, please DELETE the RestaurantDB.sqlite before running app.py

This will allow for a clean run through demonstration of the analysis - If this file is not removed BEFORE running app.py at any stage - the DB will double up its records every time app.py is executed and the DB is not removed beforehand. 

Future implementations will have a db checker that will skip running the LOAD portion of the scripts to avoid record double ups being written to the database.


The implementation of the dashboard was constructed purely for demonstration purposes and much more front end development needs to be undertaken for the final product.

## Requirements

pandas
sqlalchemy
matplotlib
datetime
seaborn
pytrends
sklearn
tensorflow
flask

## Data Exploration and Transformation

Please refer to the Juypter notebook files located in the folder marked Documents for a step by step walk through of all exploration and transformation information.

## Findings from app execution

Running the analysis on a set of the top 10 selling items we are able to create some informative forecast projections - As this data doesn't take into account real world inputs for its predictions, unknown unknowns may still occur distrusting any predicted results, however if we use the results as a baseline for pattern recognition what we are able to do is understand what trends may be noticeable during the period of time the machine learning model predictions for. For example, analyzing the revenue data we can notice that there is a clear up trend predicted over the course of 01-2023 to 03-2023 and then a steep decline from 03-2023 to 04-2023. What we can take away from this is that as a business owner we may want to look into ideas for building stronger customer numbers over Feb and March with a possible promotional campaign leading in from March through to May in efforts to curb the predicted results. 

