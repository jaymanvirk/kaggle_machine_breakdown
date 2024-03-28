# Machine Breakdown Prediction: Test performance of LogReg, Decision Tree, RF, kNN  and SVM

## Introduction

In this kernel we're going to to predict machine breakdown based on its indicators. There are more than 50 of them and all of which are unnamed. Therefore, we also need to understand how much we can reduce the number of available dimensions to simplify calculations.

Thus we have two questions on the way:
1. Which model do we need to accurately predict machine breakdown?
2. What is the intrinsic dimension of the data provided?

Because of the provided marked data and output as classes, we have a classification problem. Thus we're going to use some of the most popular classfiying models:

- Logistic Regression
- Decision Tree
- Random Forest Classifier
- k-Nearest Neighbors
- Support Vector Machines

For the second question we're going to use the principal component analysis to reveal how many dimensions contribute to the output the most. Thus let us open the veil and figure out which indicators help us predict the future of the machine.
