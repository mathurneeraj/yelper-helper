# yelper-helper
## CS 229 Project: Recommending businesses based off of one's yelp review history

Developers: Aditi Goyal, Akayla Hackson, Neeraj Mathur

# The Yelper Helper: 
#Providing recommendations to Yelp users based on their prior review history

### Team Members: Aditi Goyal , Akayla Hackson , Neeraj Mathur (

### Project Description:

### Motivation: When searching for new restaurants and services, yelp users often have to use a trial-and-error approach to find one that fits their desires. They have to search through numerous options and read through several reviews per option to determine if it is a good fit. This process is a brute-force approach and often does not result in an optimal match. We propose a more convenient solution, by recommending restaurants and services that will best match the user's preferences. This is an application of ML on customer reviews and will employ some NLP. 
Method: We first plan to apply NLP on customer reviews to identify key characteristics of each location (price, quality, service, ambiance, etc). We will use these keywords to generate a summary about each location, so that a user can get a general sense of how that restaurant/service is, without having to read several reviews. 
Finally, we will repeat this tagging process on the user's own review history. Based on tags that often appear in one’s history, we will recommend new restaurants/locations that fit a similar profile. 
We will test a variety of ML models that will help us predict which restaurants will be a good fit. We will likely begin with simple logistic regression classifiers (good or bad ratings based on the fit). We will also explore linear regression models to generate probabilities of how likely something is to be a good fit. As mentioned above, we will also be using NLP throughout this project in order to process the review text into keywords. 
Intended Experiments: we plan to test our prediction process using synthetic reviews. We will create fake Yelp profiles with a history of Yelp reviews and will evaluate the model's success based on how many new restaurants/services are recommended, and how well of a fit they are. This ‘fit’ metric is inherently subjective, but we anticipate that the NLP tags generated will correspond well with our human-generated keywords. 
Dataset: We will use the following Yelp dataset available as JSON files. This dataset is a subset of businesses, reviews, and user data as follows
6,990,280 reviews
150,346 businesses
200,100 pictures
11 metropolitan areas
908,915 tips by 1,987,897 users
Over 1.2 million business attributes like hours, parking, availability, and ambiance
Aggregated check-ins over time for each of the 131,930 businesses

https://www.yelp.com/dataset
https://www.yelp.com/dataset/documentation/main

