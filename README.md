# Airbnb Seattle
## Project Motivation
Being a frequent user of Airbnb. This intrigued me to do an in-depth analysis of Airbnb Seattle Data to better understand how things work in the background. I wanted to answer the following questions.

#### Question 1. I wanted to know at what time of the month did listings tend to be pricier ?
#### Question 2. Do more expensive listings tend to have better reviews ?
#### Question 3. Do Super Hosts tend to charge more than Regular Hosts and do they also tend to obtain better reviews ?
#### Question 4. Designing a Machine Learning to model to predict whether a listing is made available on a particular date?

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

The files used for this project are provided in the below mentioned dropbox link.

https://www.dropbox.com/sh/fyq6mnphdcpv6fw/AADXoqzYHKdvRLF1Q5oBYW-pa?dl=0

1. calendar.csv: calendar availability of listings and price
2. listings.csv: information about all the available listings
3. reviews.csv: listing reviews by the users

## Analysis 

Question 1. I wanted to know at what time of the month did listings tend to be pricier ?"\n"
Answer 1.  From our analysis we found listings tend to be more expensive on weekends and for this particular dataset the peak season was June- August.

Question 2. Do more expensive listings tend to have better reviews?. 
Answer 2. After conducting a Sentiment Anlaysis of the reviews and computing vader scores and comparing it to the prices we found there is no linear relationship between the two.

Question 3. Do Super Hosts tend to charge more than Regular Hosts and do they also tend to obtain better reviews ?
Answer 3. After doing Statistial Tests we can say with confidence that Super Hosts don't tend to overcharge for their listings and we can ignore security deposit as it is returned if the apartment is not damaged but from our analysis we can clearlt see that Super Hosts tend to obtain better reviews than Regular Hosts.

Question 4. Designing a Machine Learning to model to predict whether a listing is made available on a particular date?
Answer 4. We were successfuly able to design a RCF Model that can predict with almost 90% accuracy whether a listing will be made available by a host or not and the most important feature for our model was price followed by the reviews.

## Modelling

1.Irrelevant fields were dropped. Type conversions were performed and rows with missing values in important fields were dropped
2.Skew Correction was performed
3.Dummies were created for Categorical Columns.
4.Only relevant features were included in the model.

## Blog

I have also published a blog for the same which can be accessed through the link mentioned below:
https://medium.com/@sidc1998/if-you-love-travelling-you-ought-to-love-airbnb-c707247bd9a3?source=friends_link&sk=b70ae5928cfba1d8816857fc60a21203

## Acknowledgements

1.Credit to the AirBnB dataset published by AirBnB and Kaggle for hosting it, the dataset here: https://www.kaggle.com/airbnb/seattle
2.SentimentIntensityAnalyzer was adapted from: https://www.nltk.org/api/nltk.sentiment.html
3.Heatmap reference: https://stackoverflow.com/questions/12286607/making-heatmap-from-pandas-datafram
4.Random Forest Classifier: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
