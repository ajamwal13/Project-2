# Project-2

## Cost-Sensitive Logistic Regression for Minimizing False Negatives

This project tackles a classification problem using logistic regression, focusing on minimizing false negatives. The repository contains a Jupyter notebook for data preparation and a Python script for model training, optimization, and evaluation.

**Data Preparation**

- The Jupyter notebook details the process of:
  - Extracting data
  - Cleaning and transforming the data
  - Exporting the cleaned data as CSV files for the model

**Logistic Regression with Cost-Sensitive Learning**

- The Python script:
  - Initializes and trains a logistic regression model.
  - Utilizes cost-sensitive learning to penalize false negatives more heavily.
  - Explores feature reduction techniques to improve model performance.
  - Evaluates the model's performance using metrics like accuracy or precision-recall curves.
  - Optimizes the model through techniques like:
    - Feature reduction (e.g., selecting the most important features)
    - LASSO and Ridge regularization to prevent overfitting
    - Adjusting the decision threshold to influence false negative rates

**Project Goals**

- Achieve high classification accuracy (>75%) or strong R-squared (>0.8).
- Minimize the number of false negatives through cost-sensitive learning and decision threshold adjustment.

**Key Findings**

The project explores the effectiveness of various techniques in logistic regression:

- Feature reduction improves model performance and reduces overfitting.
- LASSO and Ridge regularization enhance generalizability.
- Cost-sensitive learning and decision threshold adjustment significantly reduce false negatives.

**Future Work**

- Experiment with different cost functions to reflect real-world costs of misclassification.
- Explore more advanced classification algorithms like Support Vector Machines (SVMs) or ensemble methods for potential performance gains.
- Integrate the model into a production environment for real-time predictions.

**Results**

The final model demonstrates a strong performance with high accuracy and minimal false negatives. The achieved performance metrics and optimization details are documented within the Python script itself. 

**Getting Started**

1. Clone this repository.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook for data preparation (if necessary).
4. Run the Python script for model training, optimization, and evaluation.

This repository provides a comprehensive exploration of logistic regression techniques for achieving high accuracy and minimizing false negatives in a classification task.
