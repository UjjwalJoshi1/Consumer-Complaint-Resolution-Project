# Consumer Complaint Resolution Analysis Using Python
## Project Overview
This project aims to analyze consumer complaint data to predict whether a customer is disputed or not. By leveraging various Python libraries and machine learning algorithms, we can classify customer complaints and help businesses improve their customer service and product offerings.

## Objective
The primary objective is to use machine learning models to predict customer disputes based on historical complaint data. This involves data preprocessing, visualization, model building, and evaluation.

## Tools and Libraries Used
Python: Programming language,
Pandas: Data manipulation and analysis,
Seaborn & Matplotlib: Data visualization,
Sklearn: Machine learning library for model building and evaluation,
Jupyter Notebook: Development environment

## Dataset Description
The dataset contains customer complaints with the following key features:
Date received: The day the complaint was received,
Product: Product category (e.g., credit cards, loans),
Sub-product: Specific product type (e.g., mortgage, insurance),
Issue: Description of the complaint,
Company public response: Company's response to the complaint,
Company: Name of the company,
State: State where the customer resides,
ZIP code: Customer's postal code,
Submitted via: Method used to submit the complaint (e.g., web, phone),
Date sent to company: Date when the complaint was forwarded to the company,
Timely response?: Whether the company responded timely (Yes/No),
Consumer disputed?: Target variable indicating if the consumer disputed the response (Yes/No),
Complaint ID: Unique identifier for each complaint,

## Tasks Performed
Data Reading: Import data from Excel files,
Data Type Checking: Verify data types for both training and testing datasets,
Missing Value Analysis: Handle missing values, drop columns with more than 25% missing data,
Feature Extraction: Extract day, month, and year from the date fields,
New Feature Creation: Calculate "Days held" based on the date fields,
Data Imputation: Impute missing values in the "State" column,
Data Visualization: Create various bar graphs to visualize disputes based on different features using Seaborn,
Data Preprocessing: Drop unnecessary columns, convert categorical variables into dummy variables, scale data, and perform PCA for feature selection,

## Model Building: Train and evaluate multiple classifiers:
Logistic Regression,
Decision Tree Classifier,
Random Forest Classifier,
AdaBoost Classifier,
Gradient Boosting Classifier,
K-Nearest Neighbors Classifier,
XGBoost Classifier.

## Model Evaluation: 
Select the best-performing model and predict outcomes for the test dataset.

## Conclusion

This project provides a structured approach to analyzing customer complaint data and predicting customer disputes using machine learning. By following the outlined steps, businesses can gain valuable insights into customer sentiment and improve their service quality.
