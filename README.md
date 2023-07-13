# Online Shopper's Intention Prediction

This repository contains the code and resources for predicting online shopper's intention using machine learning algorithms. The goal of this project is to analyze customer behavior in online shopping websites and predict whether a customer is likely to make a purchase or not. This information can be valuable for key performance indicators and marketing analysis.

## Dataset

The dataset used for this project is the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning repository. It includes various features such as page visits, duration, bounce rates, exit rates, special day, month, operating systems, browsers, and more. The target variable is "Revenue," indicating whether a customer made a purchase or not.

## Project Overview

The project follows the data science life cycle to solve the problem. The major steps involved are:

1. Data Collection: The dataset is obtained from the UCI Machine Learning repository.

2. Data Preparation and Cleaning: Missing values are handled, and features are converted to numerical form. Categorical variables are one-hot encoded, and the data is split into training, validation, and test sets.

3. Data Exploration and Visualization: Exploratory Data Analysis (EDA) is performed to gain insights into the dataset and visualize the relationships between variables.

4. Model Building and Evaluation: Ten different machine learning algorithms are implemented, including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Naive Bayes, Decision Tree, Random Forest, Gradient Boosting, and AdaBoost. The models are evaluated using various classification metrics such as accuracy, precision, recall, F1 score, ROC curves, and more.

5. Model Selection: The best performing model is selected based on the evaluation results.

## Repository Structure

- `data/`: Contains the dataset file and any additional data required for the project.
- `notebooks/`: Jupyter notebooks with code for data cleaning, exploratory analysis, and model building.
- `models/`: Trained model files saved for future use.
- `reports/`: Generated reports and visualizations.
- `src/`: Source code and utility functions.
- `README.md`: Description of the project and instructions.


## Results

The best performing model is the Gradient Boosting classifier, which achieved an accuracy of 90.4% and an F1 score of 0.687. The model selection is based on various evaluation metrics such as accuracy, precision, recall, specificity, and area under the ROC curve.

## Conclusion

The project demonstrates the use of machine learning algorithms to predict online shopper's intention. By analyzing customer behavior and various features, the models can provide insights into whether a customer is likely to make a purchase. The findings can be valuable for businesses to optimize their marketing strategies and improve revenue.

