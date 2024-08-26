
# Logistic Regression on Titanic Dataset

## Project Overview
This project demonstrates a logistic regression implementation from scratch to predict survival on the Titanic dataset. The logistic regression model is optimized using gradient descent, and various techniques are applied for feature engineering and selection to improve model performance.

## Features
* Logistic Regression Model
* Gradient Descent Optimization
* Feature Engineering
* Feature Selection
* Feature Standardization

## Dataset
The project uses the Titanic dataset. Ensure you have the dataset file, Titanic-Dataset.csv, in the same directory as the script. You can download the dataset from Kaggle's Titanic Dataset.

## Usage
* Load and Preprocess Data: The script loads the Titanic dataset, handles missing values, and performs feature encoding.

* Feature Engineering: Polynomial features are added to capture non-linear relationships.

* Feature Selection: Recursive Feature Elimination (RFE) is used to select the most important features.

* Standardization: Features are standardized to improve gradient descent performance.

* Dimensionality Reduction: Optional PCA is applied to reduce the feature space while retaining variance.

* Model Training: The logistic regression model is trained using gradient descent with convergence tolerance.

* Evaluation: The model's accuracy is evaluated on a test set, and a confusion matrix is plotted.

## Results
The script will output:

* The cost at each iteration of gradient descent.
* The final accuracy of the model on the test set.
* A confusion matrix visualizing the model's performance.
