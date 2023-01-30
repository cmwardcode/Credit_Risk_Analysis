# Credit Risk Analysis with Supervised Machine Learning Models
## Overview of Analysis
Credit approval for loans is based on several variables such as income, credit scores, home ownership, debts, and more. To perform this analysis of risk a machine learning model would streamline this process and provide more accurate results. The purpose of this project is to construct and analyze multiple types of machine learning models to determine based on accuracy, precision, and recall scores which model would best suite the credit risk analysis project. 
## Results
#### Logistic Regression Random Oversampling

![logistic_regression_random_oversampling]( https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/logistic_regression_random_oversampling.png)

* The balanced accuracy score was 0.66.
* The precision score was 0.66 overall, 0.66 for high risk loans, and 0.67 for low risk loans.
* The recall score was 0.66 overall, 0.68 for high risk loans, and 0.65 for low risk loans.

#### Logistic Regression SMOTE Oversampling

![logistic_regression_smote_oversampling]( https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/logistic_regression_smote_oversampling.png)

* The balanced accuracy score was 0.67.
* The precision score was 0.68 overall, 0.67 for high risk loans, and 0.69 for low risk loans.
* The recall score was 0.67 overall, 0.70 for high risk loans, and 0.65 for low risk loans.

#### Logistic Regression Cluster Centroids Undersampling

![logistic_regression_cluster_centroids_undersampling](https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/logistic_regression_cluster_centroids_undersampling.png)

* The balanced accuracy score was 0.76.
* The precision score was 0.77 overall, 0.82 for high risk loans, and 0.72 for low risk loans.
* The recall score was 0.76 overall, 0.68 for high risk loans, and 0.85 for low risk loans.

#### Logistic Regression SMOTEENN Combo Sampling

![logistic_regression_smoteenn_combo_sampling](https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/logistic_regression_smoteenn_combo_sampling.png)

* The balanced accuracy score was 0.67.
* The precision score was 0.67 overall, 0.68 for high risk loans, and 0.66 for low risk loans.
* The recall score was 0.67 overall, 0.69 for high risk loans, and 0.65 for low risk loans.

#### Balanced Random Forest Classifier

![ balanced_random_forest_classifier]( https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/balanced_random_forest_classifier.png)

* The balanced accuracy score was 0.79.
* The precision score was 0.99 overall, 0.04 for high risk loans, and 1.00 for low risk loans.
* The recall score was 0.91 overall, 0.67 for high risk loans, and 0.91 for low risk loans.

#### Easy Ensemble Classifier

![ easy_ensemble_classifier]( https://github.com/cmwardcode/Credit_Risk_Analysis/blob/main/easy_ensemble_classifier.png)

* The balanced accuracy score was 0.93.
* The precision score was 0.99 overall, 0.07 for high risk loans, and 1.00 for low risk loans.
* The recall score was 0.94 overall, 0.91 for high risk loans, and 0.94 for low risk loans.
## Summary
To assess the performance of difference machine learning models it is recommended that we consider balanced accuracy, precision, and recall. The model with the highest balanced accuracy score is the Easy Ensemble Classifier. The highest precision score is both the Balanced Random Forest Model and the Easy Ensemble Classifier with a score of 0.99. However, both of those models produced extremely low precision score for both high and low risk loans. The Easy Ensemble Classifier has the highest recall score of 0.94 overall with similar performance for both high and low risk loans. Based on these results the Easy Classifier model yields the best all encompassing scores. So I would recommend this model. However, the model has a large room for improvement with the precision score for both high and low risk loans. Therefore, I recommend proceeding with this model but not implementing for daily use until the precision score is improved through further testing. 

