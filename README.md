# Airbnb Price Prediction-Regression project

In this project we take data of Airbnb listings in the US and try to predict the price of stay in that listing.
The source of the dataset:
https://drive.google.com/file/d/1U4YmROobX45881KGNWtQLFkjWG64hNa0/view?usp=sharing

The data includes 74411 listings and 29 columns - including log_price, what we are trying to predict.
Some columns will not be used as features, such as ID and thumbnail URL, so we are left with 26 columns to process and consider as features.
There was no information about this data so we assume that since all the listings are in the us, the price (or log_price) that we are trying to predict is the general pricing per 1 night stay of the listing, in USD, not for specific dates/seasons and not including additional fees, i.e. cleaning and airbnb service fees.

The data is for 6 cities across the US: NYC, LA, San Francisco, Washington DC, Boston and Chicago.
