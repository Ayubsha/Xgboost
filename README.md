# Xgboost
XGBoost is optimized Gradient Boosting algorithm through parallel processing, tree-pruning,handling missing values and regularization to avoid overfitting bias

Gradient boosting is a technique that involves creating new models that estimate the residuals or errors of previous models, which are then combined to make the final prediction. Gradient boosting gets its name from the fact that it uses a gradient descent algorithm to mitigate loss while inserting new models.
We go through a series of cycles in which we generate new models and merge them into an ensemble model. We begin the cycle by calculating the errors for each observation in the dataset using an existing model. Then, in order to predict these errors, we build a new model. This error-predicting model's predictions are applied to the "ensemble of models."
