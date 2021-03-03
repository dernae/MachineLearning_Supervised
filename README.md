# Module_17_MachineLearning_Supervised

## Overview of Analysis

The analysis utilizes a credit card dataset from a peer-to-peer lending group. The purpose of the analysis is to 
evaluate the performances of two new Machine Learning models: BalancedRandomForestClassifier and EasyEnsembleClassifier 
on their ability to predict credit risk. For this analysis I employed different techniques to train and evaluate models 
with unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Results

### Random Forest Classifier Model
- The Random Forest Model had an accuracy score of 99.6% and precision of 73% and 100% 
<br><br>
![](https://github.com/dernae/Module_17_MachineLearning_Supervised/blob/main/results/Balanced_random_Forest.PNG)<br>
<br><br>

### Ensemble AdaBoost Classifier
- The AdaBoost Classifier had an accuracy of 99.5% and precision of 100% and 19% 
![](https://github.com/dernae/Module_17_MachineLearning_Supervised/blob/main/results/Boosting_Classifier.PNG)<br>
<br><br>

### Naive Random Oversampling Model
- The Naive Random Oversampling Model Ensemble  had an accuracy of 64.4% and precision of 100% and 1% 

![](https://github.com/dernae/Module_17_MachineLearning_Supervised/blob/main/results/oversampling.PNG)<br>
<br><br>

## SMOTE Oversampling Model 
- The SMOTE Random Oversampling Model had an accuracy of 64.8% and precision of 1% and 100% 
![](https://github.com/dernae/Module_17_MachineLearning_Supervised/blob/main/results/SMOTE.PNG)<br>

## Summary 

Overall, the Random Forest Classifier Model performed the best, the accuracy and precision scores are high (above70%).
Naive Random Oversampling Model and SMOTE Oversampling Model performed the worst, The accuracy score and cummulative 
precision scores are very low (below70%). Even though the Ensemble AdaBoost Classifier had a high accuracy score, The results were
biased and only accurate for one outcome. I would recommend using the Random Forest Classifier Model for ML 
analyses such as predicting credit risk.
