# Coursera UW Machine Learning: Regression

Course can be found [here](https://www.coursera.org/learn/ml-regression)

Notebook for quick search can be found [here](https://ssq.github.io/2017/08/19/Coursera%20UW%20Machine%20Learning%20Specialization%20Notebook/)

- Week 1:
  - Simple Linear Regression:
    - Describe the input (features) and output (real-valued predictions) of a regression model
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters to minimize RSS using gradient descent
    - Interpret estimated model parameters
    - Exploit the estimated model to form predictions
    - Discuss the possible influence of high leverage points
    - Describe intuitively how fitted line might change when assuming different goodness-of-fit metrics
    - [x] [Fitting a simple linear regression model on housing data](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%201) 
- Week 2:
  - Multiple Regression: Linear regression with multiple features
    - Describe polynomial regression
    - Detrend a time series using trend and seasonal components
    - Write a regression model using multiple inputs or features thereof
    - Cast both polynomial regression and regression with multiple inputs as regression with multiple features
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters of a general multiple regression model to minimize RSS:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Interpret the coefficients of a non-featurized multiple regression fit
    - Exploit the estimated model to form predictions
    - Explain applications of multiple regression beyond house price modeling
    - [x] [Exploring different multiple regression models for house price prediction](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%202)
    - [x] [Implementing gradient descent for multiple regression](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%203)
- Week 3:
  - Assessing Performance
    - Describe what a loss function is and give examples
    - Contrast training, generalization, and test error
    - Compute training and test error given a loss function
    - Discuss issue of assessing performance on training set
    - Describe tradeoffs in forming training/test splits
    - List and interpret the 3 sources of avg. prediction error
      - Irreducible error, bias, and variance
    - Discuss issue of selecting model complexity on test data and then using test error to assess generalization error
    - Motivate use of a validation set for selecting tuning parameters (e.g., model complexity)
    - Describe overall regression workflow
    - [x] [Exploring the bias-variance tradeoff](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%204)
- Week 4:
  - Ridge Regression
    - Describe what happens to magnitude of estimated coefficients when model is overfit
    - Motivate form of ridge regression cost function
    - Describe what happens to estimated coefficients of ridge regression as tuning parameter λ is varied
    - Interpret coefficient path plot
    - Estimate ridge regression parameters:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Implement K-fold cross validation to select the ridge regression tuning parameter λ
    - [x] [Observing effects of L2 penalty in polynomial regression](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%205)
    - [x] [Implementing ridge regression via gradient descent](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%206)
- Week 5:
- Week 6:
- Week 7:
