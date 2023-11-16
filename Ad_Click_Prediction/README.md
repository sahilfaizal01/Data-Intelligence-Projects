# Ad Click Prediction

## Introduction
* The online advertisement industry has become a multi-billion industry, and predicting ad CTR (click-through rate) is now central. Nowadays, different types of advertisers and search engines rely on modeling to predict ad CTR accurately.
* I aim to predict the ad click-through rate using machine learning techniques.
* CTR is the metric used to measure the percentage of impressions that resulted in a click.
<img width="501" alt="ctr-formula" src="https://github.com/sahilfaizal01/Data-Intelligence-Projects/assets/106440078/689ee7b3-e3aa-44f4-a929-59df595b3164">

* Search ads are the advertisements that are displayed when a user searches for a particular keyword.
* Paid search advertising is a popular form of Pay-per-click (PPC) advertising in which brands or advertisers pay (bid amount) to have their ads displayed when users search for specific keywords.

## Real-world Example
* Typically, the primary source of income for search engines like Google is through advertisement.
* Many companies pay these search engines to display their ads when a user searches for a particular keyword. Our focus is on search ads and CTR, i.e., the amount is paid only when a user clicks on the link and redirects to the brand’s website.
* Different advertisers approach these search engines with their ads and the bidding amount to display their ads.
* The main objective of these search engines is to maximize their revenue. So the question is, how does a search engine decide which ads to display when a user searches for a particular keyword?
* Now, I will explore how to calculate ad click prediction by building a Logistic Regression model that will help us predict whether a user will click on an ad or not based on the features of that user. Hence, calculate the probability of a user clicking on an ad.
* Using these probabilities, search engines could decide which ads to display by multiplying the possibilities with the bid amount and sorting it out.

## Problem Statement
In this project, I will work with the advertising data of a marketing agency to develop a machine-learning algorithm that predicts if a particular user will click on an advertisement.

The data consists of 10 variables:
* 'Daily Time Spent on Site' - Independent Variable - consumer time on-site in minutes
* 'Age' - Independent Variable - customer age in years
* 'Area Income' - Independent Variable - Avg. Income of geographical area of consumer
* 'Daily Internet Usage' - Independent Variable - Avg. minutes a day consumer is on the internet
* 'Ad Topic Line' - Independent Variable - Headline of the advertisement
* 'City' - Independent Variable - City of consumer
* 'Male' - Independent Variable - Whether or not the consumer was male
* 'Country' - Independent Variable - Country of consumer
* 'Timestamp' - Independent Variable - Time at which consumer clicks on Ad or closed window
* 'Clicked on Ad' - Dependent Variable - 0 and 1 (clicked)

I will be using these 9 independent variables to accurately predict the value 'Clicked on Ad' variable. An exploratory data analysis will also be done to understand the existing relationships in the data

