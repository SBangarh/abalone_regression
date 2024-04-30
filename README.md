# abalone_regression

## Purpose
The purpose of this repo is to submit a file into the Kaggle Playground Series - Season 4, Episode 4. Regression with a synthetic Abalone dataset that was inspired by the actual dataset from UCI.

This repo and playground series in general is a medium for me to practice data science.

## Process
I started by loading the data and engineering a few features for the data. Next, I performed EDA and explored some transformations that would normalize the data a bit. I perform some statisitcal tests to the best of my ability, but I did not realize the pvalue can become misleading if the observations are over a certain threshold. 

Once I settiled on an appropriate normalization technique, I started modelling. I started with LinearRegression, but settled on XGBRegressor. The models weren't the greatest as I joined the competition late, but the purpose is to practice and improve and not necessarily win as these competitions are for learning.