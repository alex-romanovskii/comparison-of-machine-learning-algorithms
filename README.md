# comparison-of-machine-learning-algorithms

## The aim of the project is to compare three different boosting algorithms published over the past 10 years against the Catboost algorithm

The following articles / implementations were selected:
1. Yubin Park , Joyce Ho. "Tackling Overfitting in Boosting for Noisy Healthcare Data." IEEE Transactions on Knowledge and Data Engineering (2019) / [Github](https://github.com/yubin-park/palobst)
2. Gérard Biau, Benoît Cadre, Laurent Rouvìère, "Accelerated Gradient Boosting",2018, arXiv:1803.02042 / [Github](https://github.com/msangnier/optboosting)
3. "Rie Johnson, Tong Zhang. ""Learning Nonlinear Functions Using Regularized Greedy Forest"". IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE (2014 )
" / [Github](https://github.com/RGF-team/rgf)

The algorithms were compared using the example of solving the regression problem

## Study plan
1. Evaluate 100 datasets (UCI Machine Learning Repository: Data Sets) using 10 external fold cross validation and a selection parameter with 3 internal fold cross validation. 
2. Using the MSE parameter as an example, statistically evaluate the differences between the algorithms (nonparametric Friedman test was used)
3. Using meta-features about datasets, train a model using xgboost as an example to predict the best algorithm

## For details you can see [report](https://github.com/alex-romanovskii/comparison-of-machine-learning-algorithms/blob/master/project.pdf) or [code](https://htmlpreview.github.io/?https://github.com/alex-romanovskii/comparison-of-machine-learning-algorithms/blob/master/project.html)
