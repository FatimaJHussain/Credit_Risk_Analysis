# Credit_Risk_Analysis

## Overview
We use various ML algorithms to find the Credit risk for the given dataset (redit card credit dataset from LendingClub). Credit risk is an unbalanced classification problem, because there is less number of risky loans as compared to good loans. We use  imbalanced-learn and scikit-learn libraries to train and evaluate models with unbalanced classes. 

We oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Afterwards, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results
In the following line, we discuss the details for Logistic Regression and Random Forets models and prediction results.
### Logistic Regression 
* Random Over SamplerIt has balanced_accuracy_score of 0.67, precison of 0.01 and recall of 0.74, as shown in figure-1 below.

Figure-1: Naive Random Oversampling![Naive Random Oversampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/Randomoversampler.png).
* SMOTE Oversampling: It has balanced_accuracy_score of 0.66, precison of 0.01 and recall of 0.63, as shown in figure-2,3 below.

Figure-2: SMOTE Oversampling Report![SMOTE Oversampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTE.png).

Figure-3: SMOTE Oversampling Balanced Accuracy Score![SMOTE Balanced](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTE1.png).

* Undersampling with Cluster Centroids Resampler: It has balanced_accuracy_score of 0.544, precison of 0.01 and recall of 0.69, as shown in figure-4 below.

Figure-4: Undersampling using ClusterCentroids Resampler![Undersampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/CLUSTER.png).

* Combination Sampling using SMOTEENN: It has balanced_accuracy_score of 0.64, precison of 0.01 and recall of 0.71, as shown in figure-5 below.

Figure-5: Combination (Over and Under) Sampling using SMOTEENN![SMOTEENN](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTEENN.png).
### Random Forest
* Balanced Random Forest Classifier: It has balanced_accuracy_score of 0.769, precision 0.03 and recall of 0.66, as shown in the figure-6 below:

Figure-6: Balanced Random Forest Classifier![Random Forest](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/FOREST.png).
### Ensemble  AdaBoost Classifier
* Ensemble AdaBoost Classifier: It has balanced_accuracy_score of 0.93, precision 0.09 and recall of 0.92 , as shown in the figure-7 below:

Figure-7: Ensemble AdaBoost Classifier![ Ensemble AdaBoost](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/ENSEMBEL.png).



## Summary

We compare accuracy scores and precison, recall for two ML algorithms Randon Forest and Logistic Regression with varrying sampling techniques. 
Considering Logistic Regression classifier, there is not much of the difference in precion of various sampling techniques but have different recall values. Logistic Regression with naive random oversampling has highest recall value of 0.74.

By inspecting Random Forest, we can see balanced_accuracy_score of 0.769, precision of 0.03 and recall of 0.66. For the AdaBoost Classifier, balanced_accuracy_score of 0.93, precision 0.09 and recall of 0.92. 

By comparing these algorithms, we can recommend Ensemble AdaBoost Classifier having preciosn of 0.09 and highest recall of 0.92
