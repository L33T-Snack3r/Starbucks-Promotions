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

#### Starbucks_Capstone_notebook.ipynb
This was the notebook where all the work of this project (data cleaning, transformation and analysis, and heuristic and model development) was conducted.

#### Figures.ipynb
This notebook was used to create the figures in the blog post. The input file is customer_summary.csv, which can be created by running Starbucks_Capstone_notebook.ipynb

## Findings
The findings of this investigation are summarized in this [blog post](https://medium.com/@thefunnyonion/unlocking-the-maze-navigating-starbucks-app-user-incentives-71a2a74063f5)

## Licensing, Authors, Acknowledgements
I would like to thank Udacity and Starbucks for making this data available. I would also like to acknoledge Harshal Soni and medium user RITHP, whose medium articles I referenced to implement hyperopt for parameter optimization. 

