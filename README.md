# Credit Risk Analysis
## Overview
The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk. In order to complete this task, I used 6 different methods, which are:

Create supervised machine learning models to predict credit risk. Using imbalanced-learn and scikit-learn libraries to create target variables, train the model, and to get accuracy and confusion matrices. The accuracy, precision, and recall scores can be observed below for Naive Random Oversampling, SMOTE Oversampling, Cluster Centroid Undersampling, SMOTEENN Sampling, Balanced Random Forest Classifying, Easy Ensemble Classifying.


![This is an image](https://i.imgur.com/yDA5Gvb.png)
![This is an image](https://i.imgur.com/eNKKQ81.png)
![This is an image](https://i.imgur.com/sTiQ5gx.png)
![This is an image](https://i.imgur.com/vR6XXVZ.png)
![This is an image](https://i.imgur.com/XmcwPCC.png)
![This is an image](https://i.imgur.com/30HxUNW.png)
![This is an image](https://i.imgur.com/NwSbTGg.png)
![This is an image](https://i.imgur.com/TNTKzRn.png)
![This is an image](https://i.imgur.com/moHpAi9.png)
![This is an image](https://i.imgur.com/Uldfjc2.png)


This analysis is trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through undetected. That correlating statistic for this is the recall rate for high risk. Looking through the different models, the ones that scored the highest were:

Easy Ensemble Classifying (91%)
SMOTEENN Sampling (76%)
Naive Random Oversampling (72%)
While this is the most important statistic that is pulled from this analysis, another important statistic is recall rate for low risk as it shows how many low risk loans are flagged as high risk. Looking through the different models, the ones that scored the highest were:

Balanced Random Forest Classifying (100%)
Easy Ensemble Classifying (94%)
After taking these two statistics over the others, we can look at the accurary score to get a picture of how well the model performs in general. The models with the highest accuracy scores were:

Easy Ensemble Classify (92.3%)
SMOTEENN Sampling (68.1%)
Balanced Random Forest Classifying (64.8%)
After factoring in these three main statistics, the model that I would recommend to use for predicting high risk loans is the Easy Ensemble Classifying model.
