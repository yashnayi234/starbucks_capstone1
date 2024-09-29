
# Starbucks-Capstone-Challenge
[Blog link here]

Table of Contents
Libraries Used
Project Motivation
Summary
File Descriptions
Licensing and Acknowledgements
Libraries Used
This project requires Python 3.x and the following libraries installed:

python==3.6.3 (recommended)
seaborn==0.8.1
pandas==0.23.3
numpy==1.12.1
matplotlib==2.1.0
sklearn==0.19.1

## Project Motivation
This project is part of the Udacity Data Science Nanodegree. It explores customer behavior data from Starbucks, simulating interactions on their rewards mobile app. Starbucks sends offers to users, which can either be advertisements, discounts, or BOGO (buy one get one free) offers. The data consists of demographic information, offer details, and interaction events related to offers.

The key goals of this project are:

Can we classify if an offer will be successfully completed based on demographic and offer information?
Build machine learning models to predict offer success.
Answer the following questions:
Which offer type is the most successful?
Who spends more money: male or female customers?

## Summary
The results of the project demonstrate that the AdaBoost classifier provided the best performance with an accuracy of 68.9%. Key 

## findings include:

Membership Duration and Income are the most influential features in determining offer success.
Females spend more money on average, which could be used to target future offers more effectively.
Discount offers are the most successful type of offer, as they have a higher completion rate compared to BOGO offers, though BOGO offers are viewed more often.

## File Descriptions
This repository contains the following files:

/data: A directory containing information about the dataset used. (The actual dataset is not included due to size constraints, but the structure is described in info_about_data.md).

Starbucks_Capstone_notebook.ipynb: The main Jupyter Notebook with all the analysis and model-building code.

Starbucks_Capstone_notebook.html: An HTML version of the Jupyter Notebook for easy viewing.

README.md: This file, containing an overview of the project and instructions.
Blog.md: A markdown file containing a blog-style summary of the project and findings.

## Licensing and Acknowledgements
This project makes use of data provided by Starbucks. The project is part of the Data Scientist Nanodegree program offered by Udacity. Special thanks to Starbucks for sharing their simulated data and to Udacity for the guidance and curriculum.

