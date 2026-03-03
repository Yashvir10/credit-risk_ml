Introduction: 
This projects dataset contains customer-related financial features like credit bills , payment history ,bill amounts ,and more over education ,sex, marriage and age .
The project is based over the prediction of whether a customer's payments will default on credict card. The major task over here is to refine the data handle cleaning and preprocessing , train multiple ML models and perform evaluation models more over the project also includes hyperparameter tuning and bias - variance curve. 
the project functions on the dataset over multiple phases and parameters.

BEST MODEL: Random Forest 
MOST IMP. Metrics: recall_score

Phase 1 (Data Understanding and EDA )
 The dataset is loaded and the path of the file is copied then the data is understood and filtered. FUrther more EDA is used to understanding the structure, patterns, and relationships within the dataset before applying models and helps visualize the model using histplot, class disrtribution and countplot

 Phase 2(Data Preprocessing)
 The data is split in train and test by 0.2 test_size and feature scaling is performed to normalize numerical values  and the data set was checked for class imbalance.

 Phase 3 (Model Building)
 Model building is the step where ML algorithms are trained on preprocessed data to predict whether a customer will default on payment.  This project uses multiple algorithms logistic regression , knn, decision tree , naive bayes , gradient boosting , random forest ,SVM .This project focuses on classification models to solve a binary target problem.

 Phase 4(Hyperparameter Tuning)
 Hyperparameter tuning is the process of optimizing model parameters that are not learned during training but significantly impact performance. Proper tuning improves accuracy, generalization, and robustness of machine learning models.

 Phase 5(Bias-Variance Analysis)
 This graph curve is used to test the conditions of underfitting and overfitting.Bias–Variance Analysis is a  concept in ML that explains model performance in terms of errors due to bias and variance to data .

 Phase 6(Final Recommendation)
 the best model here is RandomForest as it has the highest roc_auc score , handlf1es imbalance well and has a strong f1_score.
 Recall is the most important metrics out of all in credit risk prediction as it prioritized to minimize financial risk whereas the f1_score ensures balanced predictions.