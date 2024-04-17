# Fraud Detection Notebook

## Overview
This repository contains a Jupyter Notebook focused on fraud detection using machine learning techniques. The notebook covers various aspects of the fraud detection process, including data preprocessing, feature engineering, model training, evaluation, and interpretation.

## Contents
- `fraud_detection_notebook.ipynb`: Jupyter Notebook containing the fraud detection pipeline.
- `customer_transaction_details.csv`: Contains information on cusotmers transactions.
- `customers_df.csv`: Conaatins information on Customers.
- `README.md`: This README file providing an overview of the repository.

## Getting Started
To run the notebook locally, follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install the required Python packages listed in the notebook.
4. Open the `fraud_detection_notebook.ipynb` file using Jupyter Notebook.
5. Follow the instructions and execute the code cells in the notebook sequentially.

## Dataset
The dataset (`data.csv`) used in this notebook contains information about transactions, including features such as the number of orders, payments, transaction amount, customer information, and whether the transaction is fraudulent or not.

## Notebook Overview
1. **Data Preprocessing**: Cleaning and preprocessing the dataset.
2. **Feature Engineering**: Creating new features and encoding categorical variables.
3. **Model Training**: Splitting the data, training a machine learning model (Random Forest Classifier), and evaluating its performance.
4. **Feature Importance**: Identifying important features for fraud detection using techniques such as Recursive Feature Elimination (RFE).
5. **Model Evaluation**: Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.
6. **Confusion Matrix**: Visualizing the confusion matrix to understand the model's predictions.

## Results
- The trained Random Forest Classifier achieved an accuracy of 99.37% on the test data.
- Precision: 95.51%
- Recall: 94.44%
- F1-score: 94.97%

## Conclusion
The notebook demonstrates the process of fraud detection using machine learning techniques, from data preprocessing to model evaluation. The trained model shows promising results in detecting fraudulent transactions based on the selected features.
