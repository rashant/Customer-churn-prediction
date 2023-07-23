# Customer Churn Prediction - Readme

## Introduction

Customer churn prediction is a machine learning project aimed at identifying customers who are likely to churn (i.e., stop using a service) based on historical data and customer attributes. In this project, we use the Telco Customer Churn dataset to build a predictive model that can effectively predict customer churn.

## Dataset

The project directory contains the following files:

- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: This CSV file contains the Telco Customer Churn dataset. It includes information about customer attributes, services used, and whether the customer churned or not.

## Model Development

The predictive model is built using Python and Keras. The following steps are involved in developing the model:

1. **Data Preprocessing**: The dataset is loaded using pandas, and necessary preprocessing steps are performed, such as handling missing values, encoding categorical variables, and scaling numerical features.

2. **Feature Selection**: We use mutual information score to select relevant features that have a significant impact on predicting customer churn.

3. **Model Training**: The dataset is split into training and testing sets. The model architecture is defined using the Keras Sequential API, and a neural network with dense layers is created. The model is then trained on the training data.

4. **Model Evaluation**: The trained model is evaluated on the testing data, and metrics such as accuracy, precision, recall, and F1-score are calculated using the classification report.

## Directory Structure

The project directory has the following files:

- `customer churn prediction.ipynb`: This Jupyter notebook contains the Python code for data preprocessing, feature selection, model training, and evaluation. It also includes visualizations and explanations of the steps involved in the project.

- `model.h5`: This is the saved trained model in HDF5 format. It can be loaded and used for making predictions on new data without retraining.

## Conclusion

Customer churn prediction is a valuable application of machine learning that helps businesses understand and identify customers who are likely to churn. By predicting churn in advance, businesses can take proactive measures to retain valuable customers and improve overall customer satisfaction. The trained model can be deployed in production to make real-time predictions on new customer data and assist businesses in their customer retention efforts.
