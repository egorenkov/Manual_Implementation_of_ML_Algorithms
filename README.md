# **Machine Learning Algorithms from Scratch**  

This repository contains **self-implemented** machine learning algorithms in Python, covering both **classification** and **regression** tasks. The goal was to deeply understand the mathematical foundations and optimization techniques behind these models by coding them **without relying on high-level libraries like Scikit-learn** (except for NumPy for numerical operations).  

## **Implemented Algorithms**  

### **1. Multinomial Logistic Regression**  
📌 **File:** [`MultinomialLogisticRegression.ipynb`](MultinomialLogisticRegression.ipynb)  
- Implemented **softmax regression** for multi-class classification  
- Used **cross-entropy loss** and **gradient descent** for optimization  
- Tested on a custom dataset (or Iris/ MNIST digits if applied)  

### **2. K-Nearest Neighbors (KNN) Classifier**  
📌 **File:** [`KNNClassifier.ipynb`](KNNClassifier.ipynb)  
- Implemented **lazy learning** algorithm with customizable *k*  
- Supports **Euclidean & Manhattan distance metrics**  
- Evaluated on synthetic or real classification datasets  

### **3. Linear Regression (Analytical Solution)**  
📌 **File:** [`LinearRegressionAnalytically.ipynb`](LinearRegressionAnalytically.ipynb)  
- Solved **closed-form normal equations** for least squares regression  
 
### **4. Linear Regression (Iterative Solution)**  
📌 **File:** [`LinearRegressionIteratively.ipynb`](LinearRegressionIteratively.ipynb)  
- Implemented **gradient descent** (batch & stochastic variants)  
