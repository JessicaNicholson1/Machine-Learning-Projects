# An Empirical Comparison of Supervised Machine Learning Algorithms

This repo reviews the following four supervised machine learning algorithms:

1) Linear Regression
2) kNearest Neighbor
3) Random Forest Regression
4) Gaussian Process Regression

All of these will be implemented using regression predictive models resulting 
in a Mean Squared Error which is used as benchmark comparison for the performance of each model

The four algorithms have been fit to the Sarcos data set which is an inverse dynamics 
problem for a seven degrees-of-freedom SARCOS anthropomorphic robot arm. 
This data set is a well-defined functional mapping of continuous inputs x ∈ Rn to 
outputs x ∈ Rn of the same kind therefore we can view it as a regression problem;
where its task is to to learn the mapping describing the relationship from input to target, using sample data.

A final report comparing the four methods can also be found in this repo. 
