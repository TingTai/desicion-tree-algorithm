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
3. Evaluation methods：Precision, Accuracy, Recall, F1-score

## Problem statement
1. Train decision tree classifiers with all features, and report the 
testing performance scores and compare with SKlearn for correctness checking.
2. Discuss the performance differences among MissError, 
Entropy, and Gini index under CART.
3. Visualize training data using scatter plot on a 2‐
dimensional space by taking one feature on one axis 
and the other feature on another axis.
4. For CART, create plots of training and validation 
error with respect to different hyperparameters in 
your hand‐crafted implementation and sklearn.

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
