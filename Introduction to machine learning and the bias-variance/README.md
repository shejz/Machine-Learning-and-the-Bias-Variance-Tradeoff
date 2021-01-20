## **Supervised Machine Learning 1** : Introduction to machine learning and the bias-variance tradeoff

Supervised Learning is a course series that walks through all steps of the classical supervised machine learning pipeline. The course series focuses on topics like **cross validation** and **splitting strategies**, **evaluation metrics**, **supervised machine learning algorithms** (like linear and logistic regression, support vector machines, and tree-based methods like random forest, gradient boosting, and XGBoost), and **interpretability**.

> ### **Learning Objectives**
- Describe how a task like spam filtering can be solved with explicit coding instructions vs. a machine learning algorithm that learns from examples (training data).
- Summarize the similarities and differences between supervised and unsupervised ML.
- List the pros and cons of supervised machine learning.
- Define the mathematical model behind linear and logistic regression.
- Explain what the loss function is.
- Describe the two main types of regularization and why it is important.
- Perform a simple train/validation/test split on IID data
- Apply linear and logistic regression to datasets.
- Tune the regularization hyperparameter.
- Identify models with high bias and high variance and Select the best model and measure its performance on a previously unseen dataset, the test set.

### **Course Outline**
**Module 1**: Intro to Machine Learning 
- Motivation: why supervised ML is the most successful area of ML
- The example of the spam filter: workflow with explicit coding instructions vs. machine learning
- The feature matrix and the target variable
- Supervised and unsupervised machine learning
- The pros and cons of supervised ML
- Automation and predictions 

**Module 2**: Overview of linear and logistic regression with regularization 
- The mathematical models behind linear and logistic regression
- The cost function
- Brief description of gradient descent
- Motivate regularization
- L1 (Lasso) and l2 (Ridge) regularization

**Module 3**: The bias-variance tradeoff 
- Split a dataset into train/validation/test sets
- Standardize the dataset
- Train linear models with various regularization strength
- Calculate the train and validation scores
- Plot the scores and the predictions of corresponding models
- Identify regions of high bias and high variance
- Select the best regularization strength
- Calculate the test score


## Description

### Part 1: Introduction to machine learning and the bias-variance tradeoff
This course starts with a high-level overview of supervised machine learning focusing on regression and classification problems, what questions can be answered with these tools, and what the ultimate goal of a machine learning pipeline is. Then we will walk through the math behind linear and logistic regression models with regularization. Finally, we put together a simple pipeline using a toy dataset to illustrate the bias-variance tradeoff, a key concept in machine learning that drives how models are selected.

