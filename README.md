# Machine Learning Portfolio

This repository contains a collection of laboratory assignments focused on the mathematical foundations and practical implementations of Machine Learning algorithms. The projects transition from classical statistical methods to modern optimization techniques using **PyTorch**.

---

## 📂 Repository Contents

### 1. [Binary Classification & Logistic Models](TP_Logistic_regression_Mahmoud_BAJJOU.ipynb)
A deep dive into the mechanics of classification, moving from generative to discriminative models.
* **Gaussian Mixture Models:** Implementation of the Bayes classifier for synthetic datasets.
* **Decision Boundaries:** Visualizing and comparing Linear Discriminant Analysis (LDA) vs. Logistic Regression.
* **Feature Engineering:** Utilizing polynomial feature expansion to solve non-linear classification problems.
* **Model Evaluation:** Precision analysis using ROC Curves and AUC (Area Under Curve) metrics.
* **Implementation from Scratch:** A full manual implementation of Logistic Regression using Gradient Descent (without high-level libraries).

### 2. [Stochastic Gradient Descent (SGD) & PyTorch](TP-SGD-Mahmoud-BAJJOU.ipynb)
An introduction to the computational frameworks used in modern AI, focusing on optimization.
* **PyTorch Mechanics:** Working with Tensors, Autograd (automatic differentiation), and hardware acceleration (CUDA/MPS).
* **Gradient Descent:** Step-by-step implementation of the Chain Rule and Backpropagation.
* **Training Dynamics:** Tracking training vs. test loss to identify and mitigate **overfitting**.
* **Performance Monitoring:** Visualizing accuracy and loss convergence over multiple epochs.

### 3. [Avazu Click-Through Rate (CTR) Prediction](Avazu_CTR_Prediction.ipynb)
A large-scale applied project using real-world advertising data from Avazu.
* **Big Data Challenges:** Handling and preprocessing massive, highly unbalanced datasets.
* **Feature Hashing & Encoding:** Transforming categorical variables into numerical vectors suitable for modeling.
* **Temporal Analysis:** Extracting predictive features from timestamps (hour of day, day of week).
* **Real-world Evaluation:** Using Log-Loss and ROC analysis to predict the probability of an ad being clicked.

---

## 🛠 Technical Stack
* **Languages:** Python
* **Deep Learning:** PyTorch
* **Data Science:** NumPy, Pandas, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn

## 🚀 Setup and Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/MachineLearning.git](https://github.com/YourUsername/MachineLearning.git)
   ```
2. Install requirements:
   ```bash
   pip install torch torchvision pandas numpy matplotlib scipy
   ```
3. Launch Jupyter Lab or Notebook:
   ```bash
   jupyter lab
   ```

---
**Author:** Mahmoud Bajjou
   
