# Credit_Risk_Analysis

## Overview
We use various ML algorithms to find the Credit risk for the given dataset (redit card credit dataset from LendingClub). Credit risk is an unbalanced classification problem, because there is less number of risky loans as compared to good loans. We use  imbalanced-learn and scikit-learn libraries to train and evaluate models with unbalanced classes. 

We oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Afterwards, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models
### Logistic Regression 
* Random Over Sampler
Figure-1: Naive Random Oversampling![Naive Random Oversampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/Randomoversampler.png).
* SMOTE Oversampling
Figure-2: SMOTE Oversampling Report![SMOTE Oversampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTE.png).
Figure-3: SMOTE Oversampling Balanced Accuracy Score![SMOTE Balanced](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTE1.png).

* Undersampling with Cluster Centroids Resampler
Figure-4: Undersampling using ClusterCentroids Resampler![Undersampling](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/CLUSTER.png).

* Combination Sampling using SMOTEENN: Combination sampling using SMOTEENN have precison of 

Figure-5: Combination (Over and Under) Sampling using SMOTEENN![SMOTEENN](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/SMOTEENN.png).
### Random Forest
* Balanced Random Forest Classifier:
Figure-6: Balanced Random Forest Classifier![Random Forest](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/FOREST.png).

* Ensemble AdaBoost Classifier: It has balanced_accuracy_score of 0.93, precision 0.09 and recall of 0.92 , as shown in the figure below:
Figure-7: Ensemble AdaBoost Classifier![ Ensemble AdaBoost](https://github.com/FatimaJHussain/Credit_Risk_Analysis/blob/main/ENSEMBEL.png).



## Summary

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
