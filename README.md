# Machine Learning Lab Repository
This repository hosts laboratory assignments and practical exercises covering binary classification, optimization techniques, and click-through rate (CTR) prediction.

# Contents
## 1. Binary Classification and Logistic Models
This notebook explores the transition from theoretical classifiers to practical implementations of logistic regression.

- Gaussian Mixtures: Implementation of a Bayes classifier for synthetic binary classification problems.

- Linear Discriminant Analysis (LDA): Building and comparing LDA against logistic models.

- Feature Engineering: Enhancing models using polynomial feature expansion.

- Performance Metrics: Detailed analysis using ROC curves and AUC (Area Under the Curve).

- Implementation from Scratch: A complete "home-made" implementation of logistic regression using gradient descent.

## 2. Stochastic Gradient Descent (SGD) with PyTorch
A deep dive into the mechanics of neural network optimization using the PyTorch framework.

- PyTorch Fundamentals: Working with Tensors, hardware acceleration (CUDA/MPS), and automatic differentiation.

- Linear Regression: Demonstration of the chain rule and backpropagation for loss optimization.

- Optimization Algorithms: Low-level implementation and understanding of Stochastic Gradient Descent.

- Best Practices: Guidelines for tracking train/test accuracy and detecting overfitting.

## 3. Avazu CTR Prediction
An applied project focused on predicting ad performance using 11 days of real-world data from the Avazu dataset.

- Data Preprocessing: Handling massive, unbalanced datasets and performing dummy encoding on categorical variables.

- Feature Analysis: Extracting temporal features (hour, weekday) and visualizing their influence on click frequency.

- Modeling: Building and testing prediction models for high-dimensional feature vectors.

- Metrics: Using ROC curves as a primary performance metric for unbalanced classification.

## Key Libraries Used
- Data Science: numpy, pandas, matplotlib, seaborn, scipy

- Deep Learning: torch, torchvision

Author
Mahmoud Bajjou
