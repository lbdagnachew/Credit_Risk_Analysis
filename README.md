# Credit_Risk_Analysis

The purpose of this analysis was to build and evaluate various machine learning models to evaluate individual customer credit risk. The dataset used to train the models was from LendingClub, a peer-to-peer lending services company.

The machine learning algorithms used inclue:
* imbalanced-learn
* scikit-learn
* RandomOverSampler
* SMOTE algorithms
* ClusterCentroids algorithm
* SMOTEENN algorithm
* BalancedRandomForestClassifier (bias reduction model)
* EasyEnsembleClassifier (bias reduction model)

Two evaluation methods: ensemble learning and re-sampling
1. Easy Ensemble AdaBoost Classifier performs the best with our steps & dataset; therefore, we would move forward with this estimator for further predictions.
2. The oversampling recall score (with SMOTE) has the highest score for predicting both low-risk and high risk loan statuses.This is the best machine learning model to choose for further credit card analysis.
