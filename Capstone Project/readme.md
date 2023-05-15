# Starbucks capstone project

This is a project analyzing the effectiveness of Starbucks offers on customer behavior. The data is contained in three files: `portfolio.json`, `profile.json`, and `transcript.json`. 

## Prerequisites
- Python 3.6 or higher
- pandas
- numpy
- seaborn
- json
- datetime
- matplotlib
- sklearn

## Installing Dependencies
To install the required packages, run the following command:
```
!pip install pandas numpy seaborn plotly datetime matplotlib sklearn
```

## Running the Code
To run the code, first, download the necessary dataset files (`portfolio.json`, `profile.json`, and `transcript.json`) to your working directory. Then, run the Jupyter notebook `Starbucks_Capstone_notebook.ipynb` to execute the code. 

The notebook contains detailed explanations and code comments for each step of the analysis.

## Project Overview
The goal of this project is to analyze the effectiveness of Starbucks offers on customer behavior. The analysis is divided into three main parts:

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Machine Learning Model

### Data Cleaning and Preprocessing
In this step, we clean and preprocess the data, which involves handling missing values, changing data types, and creating new columns that will be used later in the analysis.

### Exploratory Data Analysis
In this step, we visualize the data and derive insights from it. We explore the relationships between different variables, the distributions of different features, and how they impact customer behavior.

### Machine Learning Model
In this step, we build a machine learning model that predicts whether a customer will complete an offer. We train and evaluate three different models: Decision Tree Classifier, Logistic Regression, and Linear Regression.

## Results
The analysis reveals that:
- The Decision Tree Classifier is the best performing model with 100% accuracy.


## Acknowledgments
- This project was completed as part of the Udacity Data Scientist Nanodegree program.
