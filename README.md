# Airbnb Seattle
Doing analysis of Airbnb Seattle Data and Predicting availability of Airbnb Listing

## Introdcution
Airbnb is one of the leading companies in the travel domain. I aim to explore trends in this data to get a deeper understanding by doing an in-depth analysis of the data. I furthermore design a model to predict availability of a specific listing.

The data will be explored implementing Cross-Industry Standard Process for Data Mining better known as CRISP-DM. The CRISP-Dm process is comprised from six steps:¶

1.Business Understanding
2.Data Understanding
3.Data Preparation
4.Modelling
5.Evaluation
6.Deployment

## Files

https://www.dropbox.com/sh/fyq6mnphdcpv6fw/AADXoqzYHKdvRLF1Q5oBYW-pa?dl=0

1.seattle.zip 
2.calendar.csv 
3.listings.csv 
4.reviews.csv 

## Analysis 

1.We found that the peak season is June-August
2.Listings are pricier on weekends.
3.Reviews and price for neighbourhoods are not directly related
4.Super Hosts tend to have better reviews than Regular Hosts
5.Super Hosts don't tend to overcharge for listings which we proved using Two Tailed Statistical Significance Test


## Modelling

1.Irrelevant fields were dropped. Type conversions were performed and rows with missing values in important fields were dropped
2.Skew Correction was performed
3.Dummies were created for Categorical Columns.
4.Only relevant features were included in the model.

## Results

1.Our model could predict with alomst 90% accuracy the availability of a particular listing.
2.We could also identify the most relevant features for the model which were the price and number of reviews followed by other fields.

## Blog

https://medium.com/@sidc1998/if-you-love-travelling-you-ought-to-love-airbnb-c707247bd9a3?source=friends_link&sk=b70ae5928cfba1d8816857fc60a21203
