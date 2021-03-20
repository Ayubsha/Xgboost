# Xgboost
XGBoost is optimized Gradient Boosting algorithm through parallel processing, tree-pruning,handling missing values and regularization to avoid overfitting bias

# Gradient boosting
Gradient boosting is a technique that involves creating new models that estimate the residuals or errors of previous models, which are then combined to make the final prediction. Gradient boosting gets its name from the fact that it uses a gradient descent algorithm to mitigate loss while inserting new models.
We go through a series of cycles in which we generate new models and merge them into an ensemble model. We begin the cycle by calculating the errors for each observation in the dataset using an existing model. Then, in order to predict these errors, we build a new model. This error-predicting model's predictions are applied to the "ensemble of models."

# Methodology
In this method go through a series of cycles in which we generate new models and merge them into an ensemble model. We begin the cycle by calculating the errors for each observation in the dataset using an existing model. Then, in order to predict these errors, we build a new model. This error-predicting model's predictions are applied to the "ensemble of models."To make a prediction, we add all of the previous models' predictions together. These predictions can be used to measure new errors, generate a new model, and add it to the ensemble.In this there is one piece that isn't part of the cycle. To begin the loop, we'll need a base prediction. Initial forecasts can be very naive in reality. Even if it makes grossly incorrect assumptions, subsequent additions to the ensemble will correct the errors.

# Requirements
XGBoost requirements and properties:
1.	Since XGBoost uses numerical vectors, all object data must be transformed.
2.	While XGBoost does not have any colinear features, it is a good idea to remove them.
# Advantages 
The two reasons to use XGBoost are :
1.	Speed of execution : When compared to other gradient boosting implementations, XGBoost is really fast.
2.	Model Performance: On classification and regression predictive modelling problems, XGBoost dominates structured or tabular datasets.
