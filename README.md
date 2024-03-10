# PRODIGY_DS_3
Task - 3: Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

# Decision Tree Classifier for Customer Purchase Prediction

## Overview

This project implements a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. It utilizes Python and the scikit-learn library for machine learning tasks and data analysis.

## Project Structure

- `data/`: Contains the dataset files used in the project.
- `decision_tree_classifier.ipynb`: Jupyter Notebook containing the code implementation of the decision tree classifier.
- `list-of-orders.csv`: CSV file containing the list of orders data.
- `order-details.csv`: CSV file containing the order details data.
- `sales-target.csv`: CSV file containing the sales target data.

## Steps Performed

1. **Data Preparation and Preprocessing**: 
    - Imported and merged the dataset files.
    - Created a binary target variable indicating purchase.
    - Selected relevant features for prediction.

2. **Model Building and Evaluation**:
    - Split the data into training and testing sets.
    - Created a decision tree classifier using scikit-learn.
    - Trained the classifier and evaluated its performance using accuracy and classification report.

3. **Visualization and Analysis**:
    - Visualized the decision tree and feature importance.
    - Analyzed feature distribution and correlations.
