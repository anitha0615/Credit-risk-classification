# Module 12 Report Template

## Overview of the Analysis
This project aims to leverage various machine learning techniques to train and evaluate the performance of the Logistic Regression Models in identiying the creditworthiness of borrowers. The models were trained using different methods and their performances were cpmapred to determine the better performing model. The predictive variables in the model are the labels 0 (Healthy loan) and 1 (high-risk loan). 


Process 
The dataset was split into features and labels, and further divided into training and testing sets.
## Results


* Machine Learning Model 1:
  * Description of Model 1 :  This model was built by instantiating a logistic regression model and training with the original training sets (X_train, y_train), fitting it to the training sets, and using it to generate 
    predictions.
* Machine Learning Model 2:
  * Description of Model 2 : This model was created by resampling the original training data using the RandomOverSampler module, instantiating a logistic regression model and fitting the resampled training sets (X_resample, 
    y_resample) to the model, and generating predictions.

 The performance of each model was evaluated based on accuracy score, confusion matrix as welll as the precision score, recall score, and f1- score in the classification report.
 
## Summary

Based on the analysis, it appears that Model 2 outperforms Model 1 in predicting high-risk loans and has an overall higher accuracy in predicting both labels. Specifically, Model 2 achieved a relatively high precision in predicting high-risk loans while correctly identifying all high-risk loans in the dataset, which is considered a relatively good performance in this context. Therefore, I would recommend using Model 2 in identifying high-risk loans and overall better accuracy in predicting labels.
