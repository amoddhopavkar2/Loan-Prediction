# Loan-Prediction
Check the credit risk and predict whether a loan will be sanctioned using Random Forest model.

## Dataset - 
'Credit Risk Dataset' is a public dataset available on Kaggle.

## Data Cleaning - 
Outliers and NaNs present in the dataset affect the accuracy of the model. These values were replaced with the median.

## Random Forest Classifier - 
Random Forest Classifier is the most accurate currently available technique of classification. In this method, a collection of unrelated decision trees work together to predict the outcome. Random Forest works well only with unrelated decision trees. More the number of trees in the forest, higher will be the accuracy of the model.
For the given task of loan prediction, a Random Forest Classifier with →
Number of Trees = 40
Max. Depth = 2
Min. leaves = 2

## Spearman Correlation - 
Spearman rank-order correlation is used to show the connection between two related columns. Spearman's correlation coefficient, (ρ, also signified by rs) measures the strength and direction of association between two ranked variables.

## Accuracy of the Model - 
Accuracy = 0.7980295566502463
∴ Accuracy ≈ 79.80%
