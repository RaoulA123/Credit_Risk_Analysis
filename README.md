# Credit_Risk_Analysis

## Overview of the project

This project is to use Machine Learning strategies such as resampling and boosting to predict credit risk before offering credit to potential customers. In addition, we will use Machine Learning for the long-term solution by creating algorithms that let us know if the person can still be a good client in the future or if it can become a risk for the company. 

## Results

The following are the results from the Imbalanced Classification report and the Balanced Accuracy score from each Machine Learning  methods used:  

### Naive Random Oversampling method:

  + A balanced accuracy score of 0.6504.
  + A high risk precision score of 0.01 and a recall score of 0.68.
  + A low risk precision score of 1.00 and a recall score of 0.62.



### SMOTE Oversampling method:

  + A balanced accuracy score of 0.6584
  + A high risk precision score of 0.01 and a recall score of 0.63.
  + A low risk precision score of 1.00 and a recall score of 0.68.


### Undersampling method:

  + A balanced accuracy score of 0.5447
  + A high risk precision score of 0.01 and a recall score of 0.72.
  + A low risk precision score of 1.00 and a recall score of 0.57.


### Combination (Over and Under) Sampling method:

  + A balanced accuracy score of 0.6449
  + A high risk precision score of 0.01 and a recall score of 0.76.
  + A low risk precision score of 1.00 and a recall score of 0.59.


### Balanced Random Forest Classifier method:

  + A balanced accuracy score of 0.7878
  + A high risk precision score of 0.04 and a recall score of 0.67.
  + A low risk precision score of 1.00 and a recall score of 0.91.

### Easy Ensemble AdaBoost Classifier method:

  + A balanced accuracy score of 0.9254
  + A high risk precision score of 0.07 and a recall score of 0.91.
  + A low risk precision score of 1.00 and a recall score of 0.94.

## Summary

Based on the results from the various Machine Learning algorithms ran, the best option to perform a credit risk analysis is "Easy Ensemble AdaBoost Classifier method." This methods provides better accuarcy score (0.09254) in the modeling as opposed to all others. Better imbalanced classification results were also observed. 
