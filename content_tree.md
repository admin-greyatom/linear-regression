# Content Tree for Linear Regression

**Learning outcomes**

- Validating linear regression assumptions
- Determining co-efficients of best fit line with the help of scikit-learn (using OLS)
- Understanding different error metrics


**Pre-requisites**

The learner is assumed to have a basic knowledge of the following:
- Basics of matrix representations - what is a matrix, how is data represented in matrix form.
- Basic knowledge of matrix operations - especially matrix multiplication, transpose and inverse.
- Descriptive stats - correlation, standard deviation, mean etc. 
- Basic Python Programming with pandas and numpy. 

**Chapter 1: Why Linear Regression?**

- 1.1 Introduction to the problem statement
    - Task: No
    - Topic Difficulty - Low
    - Story: Here, we introduce the problem statement that we will be solving throughout the concept - house price regression. We introduce the features of the dataset and the outcome that we are looking for while applying linear regression
- 1.2 Need for linear regression
    - Task: Yes
    - Topic Difficulty - Medium
    - Story: We onboard the basic intuition of linear regression via a small subset of the data. Explain the overall idea of linear regression w.r.t the house pricing problem
- 1.3 Assumptions of linear regression
    - Task: No
    - Topic Difficulty - High
    - Story: We highlight the various assumptions for linear regression - what are the assumptions, how do we check the assumptions, if assumptions are violated, how do we rectify?
	
**Chapter 2: Ordinary Least Squares**

- 2.1 Mathematics of OLS
    - Task: No
    - Topic Difficulty - High
    - Story: Here we take a deep dive into the Ordinary Least Squares method - derive it from first principles (as gently as possible) and arrive at the closed form solution of linear regression.
- 2.2 Discrete example to understand OLS
    - Task: Yes
    - Topic Difficulty - High
    - Story: We take a subset of the data to understand how ordinary least squares can be used to obtain the coefficients and show the calculations in detail. This gives clarity on the implementation of least squares on data. 	

**Chapter 3: Implementing Linear Regression using sklearn**

- 3.1 Model building with scikit-learn
    - Task: Yes
    - Topic Difficulty - Low
    - Story: Now that the learners are familiar with the internals of OLS, now is a good time to introduce the sklearn library to onboard how to actually do linear regression using sklearn. We will onboard how to fit a linear regression model on training data and predict on test data. The learner builds the model based on the predictions.  
- 3.2 Mean absolute error
    - Task: Yes
    - Topic Difficulty - Low
    - Story: Once the predictions are obtained on test data, we discuss various ways to evaluate the model. We discuss how to obtain the mean absolute error on test data predictions (of predicting sales price of a house). This evaluation metric is then applied by the learner on house prediction data.  
- 3.3 Evaluate model with RMSE
    - Task: Yes 
    - Topic Difficulty - Medium
    - Story: We discuss the motivation of using root mean squared error over mean absolute error for model evaluation and how to obtain this metric using sklearn. This evaluation metric is then applied by the learner on house prediction data.  
- 3.4 R squared
    - Task: Yes
    - Topic Difficulty - Medium
    - Story: We try to onboard what the r^2 metric stands for - how it is defined and interpreted. This evaluation metric is then applied by the learner on house prediction data.  

