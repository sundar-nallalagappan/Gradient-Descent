# Gradient-Descent
Implementation of Gradient descent to train linear model involving dataset with univariate &amp; multiple input features. 


Objective: To implement Gardient descent function to fit models for datasets having univariate or multiple input features

Gradient Descent: Learning algorithm that helps to find the best suited parameters for the model while fitting them on the training set. From the perspective of Linear regression, gradient descent will help to find slope & intercept 

Please find below approach used in this implementation,

1) Function for Gradient Descent is defined for univariate faeture. Since it is univariate, vectorization is not needed

2) Using a sample array, function defined has been verified 

3) Linear Regression & SGDRegression from Sklearn used to fit the sample data and the parameters & predictions were compared to ensure if function defined is ok or not ok

4) Function for Gradient descent was extended for multiple input features using the method of Vectorization

5) Using a sample array, Gradient descent function defined for multiple features were verified

6) Linear regression from Sklearn used to fit the model on same sample data & parameters & estimates were compared to ensure if the defined function is okay or not ok

7) Boston housing dataset:
    a) Using the custom defined gradient function, find the best parameters(slope) for all input features. Keep updating the parameters until the cost is optimized. Using the final parameters, make the predictions & calculate the metrics(R2 sscore)

    b) Use Linear Regression & SGDRegressor from Sklearn and solve the same problem

    c) Compare the parameters, r2 score across all three approaches to ensure that custom defined function is well replicated to get reliable score