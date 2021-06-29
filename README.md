# Classification on Categorical Data

## Introduction
This project aims to train a classification model that can predict if a user will accept a coupon given his/her answers 
to some survey questions. There are two parts in this project: feature engineering for categorical data and 
hyper-parameter tuning for classification.

## Dataset
The [dataset](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation) was collected via a survey on Amazon Mechanical Turk. This dataset was collected via a survey on Amazon 
Mechanical Turk by Wang et al. (2017). The survey describes different driving scenarios including the destination, 
current time, weather, passengers, etc., and then ask the person whether he or she would like to accept the coupon if he
or she is the driver. Nearly all features in in-vehicle coupon recommendation dataset are categorical, those features 
can be divided into three types: user attributes, contextual attributes, and coupon attributes.

## Models 
There are two kinds of models built in this project: baseline models and advanced models.
### Baseline Models
* linear regression
* decision tree induction
* naive Bayes
* k nearest neighbors
* linear support vector machine
### Advanced Models
* polynomial support vector machine
* Gaussian RBF support vector machine
* Random Forest
* XGBoost
* LightGBM
* CatBoost
* Neural Networks


## Version 1
The first version includes dimension reduction, feature expansion, and model stack using LightGBM, XGBoost, and CatBoost.
It is completed on Kaggle at this [link](https://www.kaggle.com/iyet1killer/classification-on-categorical-data-part-1-sklearn#Conclusion)
at **version 6**. 

## Version 2
The second version focused on feature engineering for categorical data. K-fold target encoding and k-prototypes feature 
expansion were implemented, then feature importances in random forest model were also explored. Here is the [link](https://www.kaggle.com/iyet1killer/classification-on-categorical-data-part-1-sklearn?scriptVersionId=65867494).

## Version 3
The third version will be focusing on hyper-parameter tuning using Optuna with CPU-boosted models: XGBoost, LightGBM, CatBoost,
and Neural Networks. In addition, auto-ML tools will also be implemented.

