# K-fold-crossvalidation

Auto.csv Dataset Cross Validation
This project aims to build a linear regression model to predict the miles per gallon (MPG) of a car based on various features in the Auto.csv dataset.

# Data Source
The Auto.csv dataset was obtained from the github, link is given in code. It contains information on 392 cars, including MPG, number of cylinders, horsepower, weight, and other features.

# Libraries Used
pandas
numpy
matplotlib
seaborn
sklearn
Cross Validation
We performed 10-fold cross validation on the training data using the linear regression model from scikit-learn. The mean R2 score across all folds was around 0.70, indicating a reasonably good fit.

After cross validation, we fit the model on the entire training data and evaluated its performance on the test data using the R2 score. The R2 score on the test data was around  0.70, which suggests that the model is a decent predictor of MPG based on the available features.

# Conclusion
Overall, the linear regression model was able to achieve a reasonable level of accuracy in predicting the MPG of cars in the Auto.csv dataset. However, there may be other factors not accounted for in this dataset that could impact MPG, and further investigation is needed to refine the model's predictions, as this this repository is just to demonstrate how we can check the validation of model on performing cross-validation.
