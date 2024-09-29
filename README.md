
# Starbucks-Capstone-Challenge
[Blog link here]

# Table of Contents
1. Libraries Used
2. Project Motivation
3. Summary
4. File Descriptions
5. Installation
6. Licensing and Acknowledgements

`python==3.6.3 (recommended)`
`seaborn==0.8.1`
`pandas==0.23.3`
`numpy==1.12.1`
`matplotlib==2.1.0`
`sklearn==0.19.1`

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

Installation
To run this project locally, follow these steps:

Clone the repository:
```bash
git clone https://github.com/yashnayi234/starbucks_capstone1.git`
```
Navigate to the project directory:

```cd starbucks_capstone1```
Install the required packages:

```pip install -r requirements.txt```
Usage
Open the Jupyter Notebook:

```jupyter notebook Starbucks_Capstone_notebook.ipynb```
Run the notebook cells to execute the analysis and visualize the results.

# Results
Summarize the key findings from the analysis, including customer segments, popular products, and insights into customer satisfaction.
Include relevant visualizations that support your findings.

# Conclusion
This project demonstrates the power of data analysis in understanding customer behavior and making informed marketing decisions. The insights derived can help Starbucks tailor its marketing strategies and enhance customer satisfaction.

## Licensing and Acknowledgements
This project makes use of data provided by Starbucks. The project is part of the Data Scientist Nanodegree program offered by Udacity. Special thanks to Starbucks for sharing their simulated data and to Udacity for the guidance and curriculum.

