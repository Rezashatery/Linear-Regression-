The example below uses a marketing dataset, in order to illustrate a linear regression activity.
workflow: 
1. Second experiment: compute the regression considering all the predicting variables 
    - Repeat the steps 
2. Third experiment:  
    - Fit the tree using the default hyperparameters, in order to find the 
    maximum depth of the unconstrained tree
    - Use *cross-validation* to find the optimal *maximum depth* of the tree
    - Fit the tree with the optmal `max_depth`
    - Predict and show the *root mean squared error*

3. Fourth experiment: use the RandomForestRegressor
