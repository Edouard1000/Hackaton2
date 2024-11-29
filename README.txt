# Hackaton 02 - Classification: Diabetes Health Indicators

## Overview
This project is part of the **[LEPL1109] - STATISTICS AND DATA SCIENCES** course. The objective is to classify and predict whether patients are at high risk of developing diabetes using a dataset of health indicators. The project involves data preprocessing, correlation analysis, model selection, and evaluation of classification algorithms.

## Dataset Description
The dataset is based on the Behavioral Risk Factor Surveillance System (BRFSS) survey conducted by the Centers for Disease Control and Prevention in the USA. It contains 22 features and around 70,000 entries. The features include health-related risk behaviors, chronic diseases, and use of preventive services.

## Project Structure
The project is divided into several parts:

1. **Preliminaries**
    - Importing necessary packages
    - Importing the dataset
    - Checking if the dataset is balanced
    - Scaling the dataset

2. **Correlation**
    - Generating a correlation matrix
    - Analyzing the correlation with diabetes
    - Model selection and parameter tuning
    - Precision-Recall curve and thresholding

3. **Classifiers**
    - Linear regressor
    - Logistic regressor
    - KNN regressor

4. **Validation Metrics**
    - Precision score
    - Recall score
    - F1 score

5. **Reduce the Questionnaire Size**
    - K-Fold preparation
    - Finding the right combination length/regressor
    - Visualizing the scores

6. **Visualization**
    - Visualizing the results

## Deliverables
1. A PDF report (written in LaTeX) that answers all the questions and contains high-quality figures with named axes.
2. A Python file with the classifier implementation.
3. The Jupyter Notebook used for the project.
4. All other files necessary to run the code (excluding the datasets).