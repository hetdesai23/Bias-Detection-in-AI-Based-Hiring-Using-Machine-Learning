# Bias-Detection-in-AI-Based-Hiring-Using-Machine-Learning
A machine learning project that detects bias in AI-based hiring systems by analyzing fairness metrics across sensitive attributes, aiming to promote ethical and unbiased recruitment decisions.
# Bias Detection in AI-Based Hiring

## Overview
This project explores how machine learning models can unintentionally introduce bias in hiring decisions and demonstrates basic techniques to identify such bias.

The goal is to understand how data and model behavior can affect fairness, rather than building a complex production system.

## Problem Statement
In many real-world scenarios, machine learning models are used to assist hiring decisions. However, these models can reflect biases present in the data.

This project builds a simple classification model to simulate hiring decisions and analyzes whether the model shows bias across different groups.

## Approach

### 1. Data Preprocessing
- Cleaned and prepared the dataset using Pandas  
- Handled missing values  
- Structured the data for modeling  

### 2. Model Building
- Trained a Logistic Regression model using Scikit-learn  
- Simulated hiring decisions (selected / not selected)  

### 3. Bias Analysis
- Compared prediction outcomes across different groups (e.g., gender)  
- Observed differences in selection rates  

### 4. Basic Mitigation
- Explored simple approaches like removing sensitive features  
- Analyzed how it impacts model predictions  

## Key Observations
- Models can reflect bias if the training data itself is imbalanced  
- Removing sensitive attributes (like gender) does not fully eliminate bias  
- Other features may act as proxy variables, indirectly causing bias  

## Limitations
- The model is simple and used only for demonstration purposes  
- Bias is measured using basic comparisons, not advanced fairness metrics  
- The dataset and evaluation are limited and not suitable for real-world deployment  

## Future Improvements
- Use formal fairness metrics (e.g., equal opportunity, demographic parity)  
- Apply advanced bias mitigation techniques  
- Experiment with more complex models  
- Use larger and more realistic datasets  

## Tech Stack
- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

## Learning Outcomes
- Bias in AI is not just a model issue, but also a data issue  
- Even simple models can produce unfair outcomes  
- Building responsible AI systems requires careful analysis beyond accuracy  

## Author
Het Desai
