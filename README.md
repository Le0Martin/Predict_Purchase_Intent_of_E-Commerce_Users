# Using SVM to Predict Purchase Intent of E-Commerce Users

## Project Overview

This project aims to evaluate which attributes influence a user's online purchasing decisions and build a predictive model to forecast future purchases. Using the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning Repository, we explore various models to identify the best-performing one for predicting purchase intentions.

## Technologies Used

- *Programming Language:* Python 3.9.7
- *Libraries and Frameworks:*
  - *Pandas:* Data manipulation.
  - *NumPy:* Numerical operations.
  - *Seaborn:* Data visualization.
  - *Matplotlib:* Data visualization.
  - *Scikit-learn:* Machine learning algorithms and model evaluation.
- *Environment:* Jupyter Notebook

## Project Features

### Model Building, Training, Evaluation, and Selection Process for Classification

*Objective:* Evaluate which attributes influence a user's online purchasing decisions and build a predictive model to forecast future purchases.

### Problem Statement & Data Source

The dataset consists of feature vectors belonging to 12,330 online sessions. It was formed such that each session belongs to a different user over a period of one year to avoid any bias towards a specific campaign, special day, user profile, or period.

The dataset consists of 10 numerical attributes and 8 categorical ones. The 'Revenue' attribute can be used as the class label.

### Models Used
* Base Model with Linear Kernel
* Model with Linear Kernel and Standardized Data (Scaled)
* Hyperparameter Optimization with Grid Search and RBF Kernel
* Hyperparameter Optimization with Grid Search and Polynomial Kernel

## Conclusion

This project successfully demonstrates the use of Support Vector Machines (SVM) to predict the purchase intent of e-commerce users. By testing various kernels and performing hyperparameter optimization, the most effective model can be selected to assist e-commerce businesses in understanding and predicting customer purchase behavior.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Le0Martin/Lodz_Project.git
