# Starbucks-Promotions
This repository contains the Jupyter notebook used in the analysis of the Starbucks dataset provided by Udacity for the capstone project

## Installations
The Anaconda distribution is required to run the code in this repository. 
The necessary libraries to run all the notebooks are: 
- pandas
- numpy
- seaborn
- scipy
- scikit-learn
- matplotlib
- xgboost
- hyperopt
- kmeans1d
  
Most of the above libraries should come pre-installed with Anaconda.
The version of python used for this investigation is Python 3.10.9. 

## Motivation
This investigation was conducted for the capstone project of the Udacity Data Science Nanodegree. 

Promotion offers can be a powerful tool to bring profits or build customer loyalty, but overuse or ineffective use of promotions can instead backfire.

Provided with a simulation dataset containing a list of Starbucks app users, offers and app usage logs, I attempted to achieve the following:

1. Identify the factors that influence the likelihood of a user responding to a buy one get one (BOGO) or discount offer
2. Create and evaluate set of heuristics for identifying the user groups are more responsive to offers
3. Develop a model for predicting user response to BOGO, discounts, or either type of offer

Achieving the above goals could help Starbucks optimize profits by targeting promotions at the right users.

## Files in this repository

#### portfolio.json
This file contains information about the offers, including the offer id, the type of offer, and its duration. There are 3 types of offers in this dataset -buy one get one free (BOGO) offers, discount offers, and advertisements, but in this work, I focus only on BOGO and discount offers, of which there are 4 of each within this dataset.

#### profile.json
This file contains information about the app users, including age, gender, income and the date that they created an app account.

#### transcript.json
This file is a log of events related to each app user over a 30-day test period. Events include:
- Offer received event
- Offer viewed event
- Offer completed event
- Transaction event

If the event is offer-related, the offer id is also recorded, but if the event is a transaction event, the amount spent is recorded instead. The time at which each event occurs (in hours since the start of the test) is also recorded.

#### Starbucks_Capstone_notebook.ipynb
This was the notebook where all the work of this project (data cleaning, transformation and analysis, and heuristic and model development) was conducted.

#### Figures.ipynb
This notebook was used to create the figures in the blog post. The input file is customer_summary.csv, which can be created by running Starbucks_Capstone_notebook.ipynb

## Findings
The findings of this investigation are summarized in this [blog post](https://medium.com/@thefunnyonion/unlocking-the-maze-navigating-starbucks-app-user-incentives-71a2a74063f5)

## Licensing, Authors, Acknowledgements
I would like to thank Udacity and Starbucks for making this data available. I would also like to acknoledge Harshal Soni and medium user RITHP, whose medium articles I referenced to implement hyperopt for parameter optimization. 

