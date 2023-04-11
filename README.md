# Credit_Risk_Analysis

## Overview of the project

This project is to use Machine Learning strategies such as resampling and boosting to predict credit risk before offering credit to potential customers. In addition, we will use Machine Learning for the long-term solution by creating algorithms that let us know if the person can still be a good client in the future or if it can become a risk for the company. 

## Results

The following are the results from the Imbalanced Classification report and the Balanced Accuracy score from each Machine Learning  methods used:  

### The Naive Random Oversampling method has:

  + A balanced accuracy score of 0.63669.
  + A high risk precision score of 0.01 and a recall score of 0.62.
  + A low risk precision score of 1.00 and a recall score of 0.65.



### The SMOTE Oversampling method has:

  + A balanced accuracy score of 0.63027.
  + A high risk precision score of 0.01 and a recall score of 0.62.
  + A low risk precision score of 1.00 and a recall score of 0.64.


### The Undersampling method has:

  + A balanced accuracy score of 0.63669.
  + A high risk precision score of 0.01 and a recall score of 0.59.
  + A low risk precision score of 1.00 and a recall score of 0.43.


### The Combination (Over and Under) Sampling method has:

  + A balanced accuracy score of 0.51027.
  + A high risk precision score of 0.01 and a recall score of 0.70.
  + A low risk precision score of 1.00 and a recall score of 0.57.


### The Balanced Random Forest Classifier method has:

  + A balanced accuracy score of 0.78776.
  + A high risk precision score of 0.04 and a recall score of 0.67.
  + A low risk precision score of 1.00 and a recall score of 0.91.

### The Easy Ensemble AdaBoost Classifier method has:

  + A balanced accuracy score of 0.92542.
  + A high risk precision score of 0.07 and a recall score of 0.91.
  + A low risk precision score of 1.00 and a recall score of 0.94.

## Summary

According to all the results we got during the project and based on all the different methods we used, we can say that the best option to perform a credit risk analysis is to use the "Easy Ensemble AdaBoost Classifier method." This method not only surpasses all the others' balanced accuracy scores but also the high and low risk precision scores along with the total recall score. Due to these facts, the Easy Ensemble AdaBoost Classifier method is the best option for companies, banks, or any other financial institutions to use in order to avoid present and future credit risks.
