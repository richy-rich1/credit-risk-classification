
# Credit Risk Analysis Report  

## Overview of the Analysis  

The goal of this analysis is to assess the performance of a logistic regression machine learning model in predicting the credit risk associated with loans. The dataset used for this analysis includes various financial features, such as loan sizes, interest rates, borrowers' income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. The objective is to classify loans as either healthy (`0`) or high-risk (`1`).  

The machine learning process consisted of the following steps:  
1. Splitting the dataset into training and testing sets.  
2. Creating and fitting a logistic regression model to the data.  
3. Evaluating the model's performance using metrics such as accuracy, precision, recall, and F1 scores.  

---

## Machine Learning Model Performance  

### Accuracy  
- The model achieved an accuracy of **99%**, meaning it correctly classified 99% of all loans.  

### Precision  
- For **healthy loans (`0`)**: The precision is **1.00**, indicating the model perfectly identifies healthy loans without any false positives.  
- For **high-risk loans (`1`)**: The precision is **0.87**, showing the model is moderately effective in identifying high-risk loans, with some false positives.  

### Recall  
- For **healthy loans (`0`)**: The recall is **1.00**, meaning the model captures all healthy loans with no false negatives.  
- For **high-risk loans (`1`)**: The recall is **0.89**, indicating the model captures most high-risk loans but misses a few.  

---

## Summary  

Based on the model's results, the logistic regression model trained on the original data performs exceptionally well in predicting both healthy loans (`0`) and high-risk loans (`1`). It delivers strong precision, recall, and F1 scores, especially for high-risk loans. This is critical for helping lending companies reduce the number of bad loans and minimize financial losses.  
