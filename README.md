# Binary-classification-using-ML
Implementation of SVM, Neural Network, AdaBoost, and Random Forest classifiers 

# Classification Methods on Synthetic Dataset

## Project Goal
This project implements multiple classifiers on a synthetic dataset with 5,000 records to predict a binary target variable. It demonstrates a full machine learning pipeline, including data preprocessing, model training, hyperparameter tuning, prediction, and saving results.

## Dataset
- **Records:** 5000  
- **Columns:**  
  - `target`: observed target values (1 or -1)  
  - `features_1` ... `features_20`: input features  
- **Training set:** first 60% of data (3000 records)  
- **Test set:** last 40% (2000 records, target values masked for evaluation)

## Methods Used
- Linear Support Vector Machine (SVM)  
- Shallow Neural Network (1 hidden layer)  
- AdaBoost  
- Random Forest  

Each method is trained on the training set and used to predict the test set. The notebook also compares the models based on validation accuracy.  

## Requirements
Install the required Python packages:

```bash
pip install -r requirements.txt

