# Mercedes-Benz-Bench-Time-Reduction-Regression
Neural Network and XGBoost Regression Models to Predict to reduce cars spends on test bench

Build Models to predict and reduce the time that cars spend on the test bench.
Have to work with dataset representing different permutations of features in a Mercedes-Benz car
to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, 
resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards


Includes Principal Component Analysis,

1 Deep Neural Network Regression Model and 

4 Machine Learning Models - XGBoost with cross validation, Ridge, Lasso, Elasticnet

Neural Network Model has 11 Layers (3 Fully Connected) and 415,169 Parameters. 
Batch Normalization, Dropout Layers and Regularization included

Data is heavily binary in nature; 16 variables with zero variance, 340 out of 368 features binary and 
the remaining features too do not have much variation; as a result of this none of the models performed well.

Ridge and Deep Neural Network Models got the maximum R squared values of around .66
