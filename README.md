# Financial-Market-Prediction-with-Logistic-Regression-and-Decision-Trees
This project utilizes machine learning techniques, specifically logistic regression and decision trees, to predict the direction of the financial market based on historical stock data. It involves data collection using the Yahoo Finance API, data preprocessing, feature scaling, model training, and evaluation. The goal is to compare the performance of logistic regression and decision trees in predicting market trends.

Introduction:
This project aims to predict the direction of the financial market using machine learning techniques, specifically logistic regression and decision trees. Historical stock data is collected from the Yahoo Finance API and utilized for model training and evaluation.

Installation:
To run this project, you need to install the required packages using pip:
pip install yfinance numpy scikit-learn

Usage:
Run the Jupyter Notebook file Financial_Market_Prediction.ipynb.
Ensure that you have an active internet connection to fetch data from the Yahoo Finance API.
Follow the code cells sequentially to:
Install necessary packages
Collect historical stock data
Preprocess the data
Train logistic regression and decision tree classifiers
Evaluate the classifiers' performance
Review the results and analysis provided in the notebook.

Results:
The logistic regression classifier achieved an accuracy of approximately 54.67% on the test dataset.
The decision tree classifier achieved an accuracy of approximately 47.31% on the test dataset.
Further analysis includes precision, recall, and F1-score metrics for both classifiers.

Conclusion:
Classifier 1 (logistic regression) outperformed Classifier 2 (decision tree) in terms of accuracy.
Classifier 1 showed a trade-off between precision and recall, while Classifier 2 had a lower overall accuracy but a higher precision.
The choice between the classifiers depends on the specific requirements and trade-offs between precision and recall.
