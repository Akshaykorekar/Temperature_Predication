In this notebook I'll be using a LSTM NN to predict the temperature based on past observations. For this purpose, the steps followed are:

Downsampling of the measurements to 1 every 12 hours
Normalization of both feature and target variables
Usage of the last 100 entries (120 hours, 5 days) to predict the next 50 entries (60 hours, 2.5 days)


# Temperature_Predication
First Download dataset from : https://www.kaggle.com/katerpillar/meteonet


NW_Ground_Stations

*NW_Ground_Stations_2016.csv
*NW_Ground_Stations_2017.csv
*NW_Ground_Stations_2018.csv

Run any one file .ipynb or .py
