# Prediction of Players' Position using Machine Learning

This repository contains a machine learning project that predicts football players' positions based on their performance statistics. The project uses various machine learning algorithms to analyze player attributes and determine their most suitable playing position.

## Dataset

- `players_stats_by_season_with_position.csv`: Final dataset containing player statistics along with position information.

## Project Structure

### Data Preparation
- `Filter.ipynb`: Jupyter Notebook that handles data preprocessing and merges multiple datasets to create the final dataset.

### Model Implementation
The project implements various machine learning models to compare their performance:
- `Logistic_Regression.ipynb`: Implementation of Logistic Regression model
- `SVM.ipynb`: Implementation of Support Vector Machine classifiers with different feature transformations
- Additional model implementations may be added by contributors

## Current Results
Logistic Regression: 
- Successfully used validation and test split Did scaling
- Used right logistic regression solver saga
- Added Regularization (penalty and l1ratio Drew the feature coefficient)
- Did the decision boundaries
- Used Regularizatin to prevent verfit and underfit

Accuracy: 1660 with feature 6 and got 63 percent Accuracy

SVM: 
- All things work 

Accuracy: 79-85% accuracy with +10 features


## Getting Started

1. Clone the repository
2. Install required dependencies
3. Create a notebook to get started! (Refer to SVM.ipynb on how data is prepared before beginning with the data)


players_stats_by_season_with_position.csv – Final dataset containing player statistics along with position information. Filter.ipynb – Jupyter Notebook that merges multiple datasets to create the final dataset. Logistic_Regression.ipynb – Jupyter Notebook that applies Logistic Regression to predict player positions based on statistics. 




