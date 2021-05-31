# Credit_Risk_Analysis

## Overview
  The purpose of this project is to apply machine learning to solve a real-world challenge of credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques will be applied to train and evaluate models with unbalanced classes. The data used is from a credit card credit dataset from LendingClub, a peer-to-peer lending services company, where it'll be oversampled using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. The combinatorial approach of over- and undersampling using the SMOTEENN algorithm will also be applied. Finally, Balanced Random Forest Classifier and Easy Ensemble Classifier new machine learning will be used as it reduces bias. 
  
 ## Results
 Naive Random Sampling (AVG/total)
  - Balanced accuracy score : 0.65
  - Precision 0.99
  - Recall 0.57
  - [Results#1]( )
  
  SMOTE Oversampling (AVG/total)
  - Balanced accuracy score : 0.658
  - Precision 0.99
  - Recall 0.68
  - [Results#2]( )
   
  Cluster Centroids resampler (AVG/total)
  - Balanced accuracy score : 0.54
  - Precision 0.99
  - Recall 0.42
  - [Results#3]( )
  
    SMOTEENN (AVG/total)
  - Balanced accuracy score : 0.54
  - Precision 0.99
  - Recall 0.58
  - [Results#4]( )

Balanced RandomForest Classifier (AVG/total)
  - Balanced accuracy score : 0.79
  - Precision 0.99
  - Recall 0.87
  - [Results#5]( )

Easy Ensemble AdaBoost Classifier (AVG/total)
  - Balanced accuracy score : 0.91
  - Precision 0.99
  - Recall 0.90
  - [Results#6]( )

## Summary
Overall, each model can be used to assess and predict which customers would be at a high or low risk based on their credit score. In the first four models where we sampled and did a combination (SMOTEENN model), we can see all had high percison at 0.99 when looking at the AVG/TOTAL when the imbalanced classification report is printed. Yet, their recall scores were all relatively low compared to the balanced Random Forest Classifier and Easy Ensemble Classifier models. We can concluded that these models are better to predict clients are approved or not due to having a high percison and recall score. Ultimelty, the Easy Ensemble AdaBoost Classifier would be recommended for assesing credit score as it had the hight scores as percision was 0.99 and recall was 0.90. 
