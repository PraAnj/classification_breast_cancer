# Sample usage of basic classification algorithms

This repo contains sample usage of widely used classification models. Famous WinconsinData breast cancer dataset is used to test all the classification models for ease of comparison. Discussions about each of the classification model were included at the end of each notebook. You can find following models in src folder,

1. Naive Bayes
2. Decision tree (C4.5 - https://github.com/michaeldorner/DecisionTrees)
3. Logistic regression.
4. Random forest
5. KNN (Nearest neighbour)
6. LVQ classifier (https://pypi.org/project/sklearn-lvq/)

Plan to implement following models/ boosting methods in the future,

1. Decision tree (ID3, CART)
2. Support Vector classifier (svm.SVC)
3. Extra Trees
4. Multiple layer perceprton (neural network)
5. Linear Discriminant Analysis
6. AdaBoost
7. Gradient Boosting
8. XGBoost/ CatBoost/ LightGBM

Future additions to the repo,

1. ROC curve added for each model to elaborate on the results.
2. Add hyper parameter tuning for all models. Currently parameter tuning is incorporated only for few.

Referece:
1. http://mlr.cs.umass.edu/ml/datasets/Breast+Cancer+Wisconsin+(Original)
2. https://www.scikit-yb.org/en/latest/api/classifier/classification_report.html
3. http://www.scikit-yb.org/en/latest/api/classifier/confusion_matrix.html
4. https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
