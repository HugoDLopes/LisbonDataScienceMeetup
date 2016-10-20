# Machine Learning Hyperparameter Search (from Grid Search to SKOPT)

This repository contains the Jupyter (formerly IPython) notebook support for the Lisbon Data Science meetup of 2016/10/19, held at Startup Lisboa, Portugal. Feel free to use it. [Link to the Meetup](https://www.meetup.com/Lisbon-Open-Data-Meetup/events/234758716/).

## Introduction
An important part of using any machine learning algorithm (such as Logistic Regression or Random Forests) is tuning the hyper parameters.  
Tools such as scikit's Grid-Search and Randomized Search have greatly improved the ability to use CPU instead of sweat and tears to tune over large hyperparameter spaces.  
More recently, a new library has appeared - Scikit-Optimize - which allows us to use Bayesian Optimization (among other things) to help find good hyperparameters with less computation resources.  

**Required Python lybraries** (latest versions if possible, you can easily install them with ***pip***)
- sklearn
- skopt
- pandas
- numpy
- scipy
- matplotlib
