# Credit_Risk_Analysis

# The purpose: 
As a lead data scientist build and evaluate machine learning model or algorithms to predict credit risk. Technique need to be used in this challenge is sampling and boosting to make model and data.

# Results:

# Deliverable 1+2

## Naive Random Oversampling

1. Accuracy score for the mode:

![score](resources/NR_accuracy_score.png)

2. Confusion matrix:

![matrix](resources/NR_confusion_matrix.png)


3.  Imbalanced classification report

![report](resources/NR_imbalanced_classification_report.png)

## SMOTE Oversampling
1. Smote Accuracy Score

![score](resources/smote_accuracy_score.png)

2. Confusion matrix

![matrix](resources/smote_confusion_matrix.png)

3. Imbalanced Classification Report

![report](resources/smote_imbalanced_classification_report.png)

## Undersampling
1. Undersampling Accuracy Score

![score](resources/undersampling_accracy_score.png)

2. Undersampling Confusion matrix

![matrix](resources/undersampling_confusion_matrix.png)


3. Undersampling Imbalanced Classification Report

![report](resources/Undersampling_Imbalanced_Classification_Report.png)


## Combination Sampling 

1. Combination Sampling Accuracy Score

![score](resources/Combination_Sampling_Accuracy_Score.png)

2. Combination Sampling Confusion matrix

![matrix](resources/Combination_Sampling_Confusion_matrix.png)


3. Combination Imbalanced Classification Report

![report](resources/Combination_mbalanced_Classification_Report.png)


# Deliverable 3

## Balanced Random Forest Classifier

1. Balanced Random Forest Classifier Accuracy Score

![score](resources/D3_balanced_Accuracy_Score.png)

2. Balanced Random Forest Classifier Confusion matrix

![matrix](resources/D3_balanced_Confusion_matrix.png)


3. Balanced Random Forest Classifier Imbalanced Classification Report

![report](resources/D3_balanced_imbalanced_Classification_Report.png)

## Easy Ensemble AdaBoost Classifier

1. Easy Ensemble AdaBoost Classifier Accuracy Score

![score](resources/EasyEnsembleAdaBoostClassifier_Accuracy_Score.png)

2. Easy Ensemble AdaBoost Classifier Confusion matrix

![matrix](resources/EasyEnsembleAdaBoostClassifier_Confusion_matrix.png)


3. Easy Ensemble AdaBoost Classifier Imbalanced Classification Report

![report](resources/EasyEnsembleAdaBoostClassifier_Imbalanced_Classification_Report.png)

# Summary:
Oversampling models has accuracy scores of 66%. Undersampling model has accuracy scores of 54%. Based on the accuracy score the combination of 2 models mentioned above did not make much difference
The random forest has accuracy scores of 78%. Ensemble boost models has accuracy scores of 93%. The ensemble model had the best precision and sensitivity for high-risk loans.
We will lose the revenue if we overmark the riskes even the high riskes or low riskes in wrong ways. 








