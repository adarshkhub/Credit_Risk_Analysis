# Credit_Risk_Analysis
Supervised Machine Learning applied to assess Credit Risk 

## Overview   
It is understood that good loans outnumber risky loans, making credit risk an unbalanced classification problem. We can use various supervised machine learning methods  to train and evaluate models with unbalanced classes. We use three types, Resampling models (oversampling with RandomOverSampler and SMOTE and undersampling with ClusterCentroids) the SMOTEEN Algorithm, and ensemble classifiers (EasyEnsembleClassifier, and BalancedRandomForest). Logistic

## Results: 

###Oversampling
![Naive Random Oversampling 1](https://user-images.githubusercontent.com/67844710/203777966-2af5b45a-bdca-480f-92ce-96d238694318.png)
![Naive Random Oversampling 2](https://user-images.githubusercontent.com/67844710/203777968-4f7cc766-bce3-4a2f-bb96-ca245f699304.png)

![SMOTE Oversampling 2](https://user-images.githubusercontent.com/67844710/203777972-7e1bf7d3-66b0-4474-bdde-4ff5d005e3ab.png)
![SMOTE Oversampling](https://user-images.githubusercontent.com/67844710/203777973-faab8899-d2cc-48eb-9a23-4e7bb8ae47c0.png)

### Undersampling
![Undersampling 1](https://user-images.githubusercontent.com/67844710/203777977-6983417c-e883-4be3-814e-d938e42bc618.png)
![Undersampling 2](https://user-images.githubusercontent.com/67844710/203777978-26ce8982-0ea6-4bdb-b1a2-7b92a74d4bf8.png)

### Combination Under/Oversampling
![SMOTEEN 1](https://user-images.githubusercontent.com/67844710/203777974-7756ab22-4e80-4391-ad0f-e9b506a9f369.png)
![SMOTEEN 2](https://user-images.githubusercontent.com/67844710/203777975-e2b9a69d-6942-4270-a9fa-c9fa460b0ed6.png)

### Balanced Random Forest Classifier
![Random Forest 1](https://user-images.githubusercontent.com/67844710/203777969-4b93b31c-ed0e-4042-b3a9-1cc3e61db27d.png)
![Random Forest 2](https://user-images.githubusercontent.com/67844710/203777971-8ce05650-2e14-404f-a5ff-497bf555cf02.png)

###Easy Ensemble Adaboost Classifier
![EasyEnsembleClassifier](https://user-images.githubusercontent.com/67844710/203777964-a373887d-0f93-4851-9712-321fa6039a6b.png)'

##Summary:

While the Easy Ensemble Adaboost Classifier is a clear top performer, with over a 90% success rate at detecting high risk credit, it still has low precision and may not be viable for professional use. Further testing should be done to see if a model with similar success and higher precision can be found.


