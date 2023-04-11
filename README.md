# Credit_Risk_Analysis

## Overview of the project

The purpose of this project is to help a fast-lending company use Machine Learning strategies such as resampling and boosting so they can predict if there is a credit risk before closing any contract with clients. In addition, we will use Machine Learning for the long-term solution by creating algorithms that let us know if the person can still be a good client in the future or if it can become a risk for the company. 

## Results

After some programming and algorithms, we were able to gather the following results:

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
