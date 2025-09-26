Age Prediction from Brain Structural Data

This repository contains the code for predicting age and age-related groups using structural brain data from seven tracts of the corpus callosum. 
The study uses tractometry to extract Fractional Anisotropy (FA) profiles and applies regression and classification models to predict age and age-related groups.

Regression Models: 
Cross-valisation strategy : KFold
1. Lasso
2. Ridge

Classification models:
Cross-valisation strategy : StratifiedKFold
1. KNN
2. Logistic Regression
3. Support Vector Machine (SVM) - Classification  --> SVC


Feature selection methods tested in Regression Models: 
1. Variance Threshold
2. SelectKBest
3. Select from model

Feature selection method tested in Classification Models: 
1. Select K Best




