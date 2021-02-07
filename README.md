# Credit_Risk_Analysis

## Overview
Oversample the data using the RandomOverSampler and SMOTE algorithms, undersample the data using the ClusterCentroids algorithm, use a combinatorial approach of over and undersampling using the SMOTEENN algorithm. We then compare BalancedRandomForestClassifier and EasyEnsembleClassifier that reduce bias, to predict credit risk. We then evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results
### Naive Random Oversampling
![Naive Random Oversampling Results](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.png)

Balanced Accuracy Score - 0.65
Precision Score - 0.99
Recall Score - 0.68

### SMOTE Oversampling
![SMOTE Oversampling Results](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/SMOTE_Resampling.png)

Balanced Accuracy Score - 0.65
Precision Score - 0.99
Recall Score - 0.67

### Cluster Centroid Undersampling
![Cluster Centroid Undersampling](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/Cluster_Centroid.png)

Balanced Accuracy Score - 0.52
Precision Score - 0.99
Recall Score - 0.41

### Combination Sampling
![Combination Sampling](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/Combination_Sampling.png)

Balanced Accuracy Score - 0.64
Precision Score - 0.99
Recall Score - 0.57

### Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest_Classifier.png)

Balanced Accuracy Score - 0.68
Precision Score - 1.00
Recall Score - 1.00

### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://github.com/Kesh0326/Credit_Risk_Analysis/blob/main/Easy_Ensemble_Adaboost_Classifier.png)

Balanced Accuracy Score - 0.92
Precision Score - 0.99
Recall Score - 0.90

## Summary

Based on the analysis and results of the 6 models above, the Easy Ensemble AdaBoost Classifier is the recommended model, with all other conditions remaining constant. This model generated the highest combination scores of Accuracy, Precision and Recall



