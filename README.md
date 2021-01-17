# Credit Risk Analysis - Supervised Machine Learning

## Overview 
A hypothetical company would like to predict credit risk analysis using machine learning. By using six different models and evaluating the performace, the company will be able to quickly identify if a loan applicant will be a good candidate for their services. 

## Results
### Balanced Random Forest Classifier
- Balanced accuracy score: 0.797
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.03)
- Recall score: 0.90 for low credit risk, 0.69 for high scredit risk
![BalancedRandomForestClassifier](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.png)
### Easy Ensamble AdaBoost Classifier
- Balanced accuracy score: 0.936
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.07)
- Recall score: 0.94 for low credit risk, 0.93 for high scredit risk
![EasyEnsambleAdaBoostClassifier](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/EasyEnsambleAdaBoostClassifier.png)
### Naive Random Oversampling
- Balanced accuracy score: 0.589
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.01)
- Recall score: 0.59 for low credit risk, 0.60 for high scredit risk
![NaiveRandomOversampling](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.png)
### SMOTE Oversampling
- Balanced accuracy score: 0.584
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.01)
- Recall score: 0.50 for low credit risk, 0.67 for high scredit risk
![SMOTEOversampling](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/SMOTEOversampling.png)
### Undersampling
- Balanced accuracy score: 0.509
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.01)
- Recall score: 0.47 for low credit risk, 0.55 for high scredit risk
![Undersampling](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)
### Combination Sampling
- Balanced accuracy score: 0.584
- Precision score: pricise for low credit risk (1.00), low percision score for high credit risk (0.01)
- Recall score: 0.50 for low credit risk, 0.67 for high scredit risk
![CombinationSampling](https://github.com/rmchartman/Credit_Risk_Analysis/blob/main/Images/CombinationSampling.png)

## Summary
Reviewing the results above, the models vary in accuracy, but the precision scores are consistantly low for predicting high credit risk. Even though the balanced accuracy score for the Easy Ensamble Model was high at 0.94, the precision score for high credit risk is not impressive, leading me to reccommend the use of none of the models above. As the point of using a model is to better determine high credit risk for this company, none of the models succeeded in precisely predicting high credit risk. 
