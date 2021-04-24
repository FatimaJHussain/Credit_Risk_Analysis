# Credit_Risk_Analysis

## Overview
We use various ML algorithms to find the Credit risk for the given dataset (redit card credit dataset from LendingClub). Credit risk is an unbalanced classification problem, because there is less number of risky loans as compared to good loans. We use  imbalanced-learn and scikit-learn libraries to train and evaluate models with unbalanced classes. 

We oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Afterwards, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models

Figure-1: Revised per School Summary without Grade 9 Scores ![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/revised+perschool1.png).


## Summary

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
