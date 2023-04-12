# Fraud Detection using Logistic Regression and Random Forest

This script demonstrates how to build and evaluate two different machine learning models to detect fraudulent activity in a dataset. Specifically, the script uses logistic regression and random forest classification models to predict whether a given transaction is fraudulent or not, based on a set of features provided in the input data. 

The script uses the popular `pandas` and `numpy` libraries for data manipulation, and `scikit-learn` for model building and evaluation. 

## Prerequisites
- Python 3.x
- `pandas`, `numpy`, and `scikit-learn` libraries

## Usage
1. Download the `data.csv` file and place it in the same directory as the script.
2. Open a terminal or command prompt, navigate to the directory where the script is located.
3. Run the script using the command `python script.py`.

## Description
1. Load the data from the `data.csv` file using `pandas`.
2. Randomly sample 10% of the data for faster processing.
3. Separate the target variable and features.
4. Split the data into training and testing sets.
5. Build and train a logistic regression model on the training data.
6. Generate predictions using the logistic regression model on the testing data and evaluate the performance using the area under the receiver operating characteristic curve (ROC AUC).
7. Build and train a random forest classification model on the training data.
8. Generate predictions using the random forest model on the testing data and evaluate the performance using the ROC AUC.
9. Perform feature selection using the random forest model and build a new logistic regression model with the selected features.
10. Generate predictions using the new logistic regression model on the testing data with selected features and evaluate the performance using the ROC AUC.
11. Print the ROC AUC scores for all three models, and the list of selected features.

## Conclusion
This script demonstrates how to build and evaluate two different machine learning models for fraud detection. The logistic regression model achieves reasonable performance on its own, but by performing feature selection with a random forest model, the performance can be further improved.
