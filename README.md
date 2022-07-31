# desicion-tree-algorithm
## Description
+ Hand-crafted decision tree algorithm
+ Including ID3, C4.5, and CART
+ Impurity: Misclassification error, Entropy, Gini index
+ Goal is to predict which valuable employees will leave next, and compare with Sklearn result.
+ Analyze different hyperparameters(Tree depth)
+ Experiment：
1. Run 10 times of 80/20 and 20/80 data splitting.
2. Use 10-fold cross validation.

## Data description
About employee information, here are features of dataset:
+ satisfaction_level [numerical]
+ last_evaluation [numerical]
+ number_project [numerical]
+ average_montly_hours [numerical]
+ time_spend_company [numerical]
+ work_accident [binary]
+ promotion_last_5years [binary]
+ sales (department) [categorical]
+ salary [categorical]
+ left (prediction target) [binary]
