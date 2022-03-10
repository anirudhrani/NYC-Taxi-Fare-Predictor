# NYC-Taxi-Fare-Predictor
## About the Dataset
The dataset I've used for this project is the New York City taxi fares dataset which is provided by Kaggle. The original dataset houses a massive 55 million records. It includes data such as number of passengers, pickup datetime, pick up and dropoff locations. This dataset allows one to visualize the density of the datapoints at a particular geographical location.
*Dataset :-* https://www.kaggle.com/c/new-york-city-taxi-fare-prediction
## Overview of this project
Data cleaning and Data visualisation played a major role in building the model and understanding various patterns in the data. The pickup and dropoff plots helped visualise the geographical location in a better way. Even though there weren't any null values in the dataset, a few anomalies were found out. For instance the latitude and longitude coordinates of a few places were faulty. So such records were discarded.

## Model
The model used here is a *DEEP FEEDFORWARD NEURAL NETWORK*. The model has 4 hidden layers, which constitutes of 128 neurons in the first layer, 64 neurons in the second, 32 in the third and 8 in the fourth. The activation used here is relu, reason being the model would be exposed to non-linearity.


