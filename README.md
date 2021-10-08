# Credit_Risk_Analysis

## Overview:

The purpose of this analysis is to apply machine learning models to aid into credit card risk. With a given dataset we are going to use diffferent techniques to come up with a model that is able to predict wheter a loan is high risk or low risk. Then we are going to evaluate the performance of these models and determine wich one is better and should be used to predict credit risk. 

## Results:

Six different machine learning models were programmed to solve this problem from which we got the following results:

### 1. Logistic Regression using Naive Random Oversampling 

![Naive Random Oversampling - Logistic Regression](https://user-images.githubusercontent.com/83261520/136582232-ea5b9da9-144c-47cb-b8ec-67a7be249417.png)

From this model we got the following results: 
- Accuraccy of 0.64.
- Precision score of 0.01 for high risk and 1.00 for low risk.
- Recall score of 0.60 for high risk and 0.69 for low risk.

### 2. Logistic Regression using SMOTE Oversampling 

![SMOTE Oversampling - Logistic Regression](https://user-images.githubusercontent.com/83261520/136582239-be73c99f-57e7-4145-bb19-92f3329f07f1.png)

From this model we got the following results: 
- Accuraccy of 0.66
- Precision score of 0.01 for high risk and 1.00 for low risk.
- Recall score of 0.63 for high risk and 0.69 for low risk.

### 3. Logistic Regression using Undersampling

![Undersampling - Logistic Regression](https://user-images.githubusercontent.com/83261520/136582251-d33bb34a-0b31-4792-9f13-9e56c1b066ed.png)

From this model we got the following results: 
- Accuraccy of 0.54
- Precision score of 0.01 for high risk and 1.00 for low risk.
- Recall score of 0.63 for high risk and 0.40 for low risk.

### 4. Logistic Regression using SMOTEENN sampling

![Combination - Logistic Regression](https://user-images.githubusercontent.com/83261520/136582275-3ebb2d32-4c9b-4e3c-9855-05496c6124ed.png)

From this model we got the following results: 
- Accuraccy of 0.64
- Precision score of 0.01 for high risk and 1.00 for low risk.
- Recall score of 0.71 for high risk and 0.58 for low risk.

### 5. Balanced Random Forest Classifier

![Balance Random Forest](https://user-images.githubusercontent.com/83261520/136582287-6d0196f9-536f-4999-9285-b752c78d27e8.png)

From this model we got the following results: 
- Accuraccy of 0.78
- Precision score of 0.03 for high risk and 1.00 for low risk.
- Recall score of 0.70 for high risk and 0.87 for low risk.
- 
### 6. Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/83261520/136582299-01d84399-a783-4034-be58-cf187a182460.png)

From this model we got the following results: 
- Accuraccy of 0.93
- Precision score of 0.09 for high risk and 1.00 for low risk.
- Recall score of 0.92 for high risk and 0.94 for low risk.

## Summary:

From all 6 models, they all seem to share similar precision, however by this metric alone we cannot 
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
