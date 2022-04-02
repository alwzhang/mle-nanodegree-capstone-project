# Udacity Machine Learning Engineer Nanodegree Capstone Project
In this capstone project, you will leverage what you’ve learned throughout the Nanodegree program to solve a problem of your choice by applying machine learning algorithms and techniques. You will first **define** the problem you want to solve and investigate potential solutions and performance metrics. Next, you will **analyze** the problem through visualizations and data exploration to have a better understanding of what algorithms and features are appropriate for solving it. You will then **implement** your algorithms and metrics of choice, documenting the preprocessing, refinement, and postprocessing steps along the way. Afterward, you will collect **results** about the performance of the models used, visualize significant quantities, and validate/justify these values. Finally, you will construct **conclusions** about your results, and discuss whether your implementation adequately solves the problem.

### Introduction
This project uses data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

### Included in this repository
- data - a folder contains original datasets
- proposal.pdf - a document defining Capstone Project proposal
- 01_EDA.ipynb - a notebook for Exploratory Data Analysis and feature enginerring
- 02_Modelling.ipynb - a notebook for Modelling
- master_df.csv - a master dataset after feature engineering, cleaning, formatting, and joining, ready to use
- report.pdf - a comprehensive report containing all the details about this Capstone Project

### Datasets
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

### Libraries
This project is developed in Python 3.6.
- jupyter
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- keras
