# Credit Card Fraud Detection using Logistic Regression 

This project uses **Logistic Regression** to detect fraudulent credit card transactions. The dataset is sourced from Kaggle.

## Project Overview
- Preprocesses the dataset by **standardizing 'Time' and 'Amount'**.
- Handles **class imbalance** using **undersampling**.
- Trains a **Logistic Regression model** and evaluates performance using:
  - Confusion Matrix
  - ROC-AUC Score
  - Classification Report

## Dataset
You can download the dataset from **Google Drive**:  
[Download Here](https://drive.google.com/file/d/1cZVzj7tbAFt5aYnwvStBLtF_JwZ40TTh/view?usp=sharing)

## Dependencies 
   To ensure that all of the required dependencies are installed, open a terminal and run:
   ```bash
   pip install pandas numpy seaborn scikit-learn imbalanced-learn matplotlib gdown
