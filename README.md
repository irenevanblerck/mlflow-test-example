# Wine Quality Prediction using scikit-learn and MLflow

This code trains a linear regression model to predict the quality of red wine based on various features, and logs the resulting model's performance and parameters using MLflow. The code reads a CSV file from a URL, splits it into training and test sets, applies feature scaling to the training set, trains the model on the training set, and evaluates its performance on the test set using root mean squared error, mean absolute error, and R-squared metrics. The resulting model is then logged using MLflow, and can be stored in a model registry.
