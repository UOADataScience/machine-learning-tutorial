# Introduction
## What is Machine Learning?
The difference between statistics and machine learning is that 
  - Statistics' aim is to explain the relationship, whereas
  - Machine learning aims to create a prediction based on collected data

## Supervised Learning 
Supervised learning are algorithms that are given examples for the right answers. The algorithms then learn from these examples, and generate predictions for new data.

### Linear Regression
Linear regression is the most basic form of learning from data. Most of you who have taken statistic or math papers should have came across this topic frequently. 

Essentially, the idea behind linear regression is that a "line of best fit" is drawn for the collected data, with the main objective of finding a relationship between 2 or more sets of data. An example below
<p align="center">
<img src="https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/regression.png" width="500">
</p>
<!-- ![alt text](https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/regression.png "Linear Regression") -->

Given a training set, a learning algorithm will generate weights based on collected data. Once the solution has converged, any new input will be passed through the calculated weights and a prediction will be generated.
<p align="center">
<img src="https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/regression_inout.png" width="500">
</p>
<!-- ![alt text](https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/regression_inout.png "Mapping from Input to Output") -->

More details are available on the [wiki](https://en.wikipedia.org/wiki/Linear_regression) page.

### Classification and Logistic Regression
For classification purposes, unlike linear regression, the output for logistic regression will only take on a small amount of discrete values. For an example, telling apart spam messages and otherwise.
<p align="center">
<img src="https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/classification.png" width="200">
</p>

### Neural Network
"Neural network" is a name given to a nonlinear function approximator, whereby inputs are mapped to output through a series of complex functions. 

Neural networks are typically drawn as such
<p align="center">
<img src="https://github.com/UOADataScience/machine-learning-tutorial/blob/master/images/neural_network.png" width="200">
</p>

## Unsupervised Learning
### K-Means Clustering Algorithm
### Principal Component Analysis
### Independent Component Analysis
## Reinforcement Learning
## Optimization
## Practical Advice
# Resources
## Books
## Online Lectures
## MOOC
# Available Packages