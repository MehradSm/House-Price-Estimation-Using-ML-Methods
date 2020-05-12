## Gradient Boosting

The following is a description of each script and an order in which you run the code:

1.	Generalizationerror.m- plots generalization error
2.	CV_25_mns_mls.m – conducts cross validation for 25 values of MaxNumSplits and 25 values of MinLeafSize
3.	Cv_mns_mls_scaled.m – conducts cross validation for 6 values of MaxNumSplits and 6 values of MinLeafSize (modified version of [2] to use for normalized data)
4.	CV_numtree_lr.m – conducts cross validation for numtrees and learning rate
5.	CV_numtrees_lr_subsampling.m – conducts cross validation for different values of number of trees, learning rate, and resample fractions
6.	Metrics_150tree_wLR.m – plots MSE, MAE, RMSE, and R^2 for training data and test data for best value of Learning Rate(results from CV_numtrees_lr_subsampling) over 150 trees
7.	Metrics_LR_500trees.m – plots the metrics for training data and test data for different values of learning and 500 trees
8.	Partialdependenceplots.m – plots single variable dependence plot and two-variable partial dependence plot

