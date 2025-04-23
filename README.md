# Self-Guided Machine Learning Course in Python

## Audience

This course is designed for software engineers, but assumes minimal experience with Python, machine learning, or mathematical statistics.

## Goals

By the end of this course, learners should be able to:

- Understand core machine learning concepts and terminology
- Use Python and key ML libraries to build basic ML models
- Perform data preprocessing, model evaluation, and improvement
- Apply ML techniques to real-world structured datasets

## Getting Started

1. Install `uv` (a Python dependency manager) by running `curl -LsSf https://astral.sh/uv/install.sh | sh`
2. Clone this repo
3. In the newly cloned repo's directory, run `uv sync` (pulls down the necessary Python packages)
4. Run `uv run jupyter lab`. This will open a Jupyter Lab interface in your default browser.

---

## Core Modules

### **Module 0: Foundations**

- Overview of Python for data science (syntax, types, control flow)
- Introduction to Jupyter Notebooks
- Installing packages and managing environments
- **Notebook:** Python quickstart for ML learners

### **Module 1: Essential Mathematics and Statistics**

- Descriptive statistics: mean, median, mode, variance, standard deviation
- Probability basics
- Distributions (normal, binomial, etc.)
- Correlation and covariance
- Basic linear algebra and matrix operations
- **Notebook:** Statistical analysis and visualization of a small dataset

### **Module 2: Introduction to Machine Learning**

- What is Machine Learning?
- Types of ML: Supervised, Unsupervised, Reinforcement
- Typical ML workflow and tools
- Real-world examples
- **Notebook:** Predict flower species using the Iris dataset

### **Module 3: Python and ML Libraries Overview**

- Python syntax review (with comparisons to Ruby/JavaScript)
- Libraries: Numpy, Polars, Altair, Scikit-learn
- Differences between Polars and Pandas
- **Notebook:** Data exploration using Polars & Altair

### **Module 4: Data Preprocessing**

- Reading and inspecting structured data
- Handling missing data
- Encoding categorical variables
- Scaling and normalization
- Train-test split
- **Notebook:** Clean and prepare the Titanic dataset

### **Module 5: Supervised Learning - Classification**

- Concepts: Labels, Features, Decision Boundaries
- Algorithms: Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Trees
- **Notebook:** Income classification with the UCI Adult dataset

### **Module 6: Supervised Learning - Regression**

- Concepts: Predicting continuous values
- Algorithms: Linear Regression, Polynomial Regression
- Regularization: Lasso and Ridge
- **Notebook:** Predict housing prices (California Housing dataset)

### **Module 7: Model Evaluation and Metrics**

- Classification: Accuracy, Precision, Recall, F1, Confusion Matrix
- Regression: MAE, MSE, RMSE, R^2
- Cross-validation concepts
- **Notebook:** Compare models using k-fold cross-validation

### **Module 8: Unsupervised Learning**

- Concepts: Discovering structure without labels
- Clustering: K-Means, Hierarchical
- Dimensionality Reduction: PCA
- **Notebook:** Cluster Iris dataset and visualize with PCA

### **Module 9: Model Selection and Hyperparameter Tuning**

- GridSearchCV and RandomizedSearchCV
- Model Pipelines in Scikit-learn
- **Notebook:** Build and tune a pipeline for classification

### **Module 10: End-to-End Real-World Project**

- Project planning and data selection
- Data cleaning, feature engineering
- Model selection, evaluation, and tuning
- Summary report and conclusions
- **Notebook:** Solve a practical structured data problem from a public dataset

---

## Optional / Advanced Modules

### **Module A: Feature Engineering**

- Creating new features from existing data
- Feature selection techniques

### **Module B: Working with Imbalanced Datasets**

- Understanding imbalance
- Resampling techniques (SMOTE, undersampling)

### **Module C: Ensemble Methods**

- Bagging and Boosting
- Random Forests, XGBoost, LightGBM
- **Notebook:** Compare ensemble models on classification

### **Module D: Time Series Basics**

- Temporal data structure
- Lag features and window statistics
- Simple forecasting with Linear Regression

### **Module E: Introduction to Deep Learning**

- Neural network basics
- Keras and TensorFlow overview
- **Notebook:** Handwritten digit recognition with Keras

### **Module F: Model Interpretability**

- Feature importances
- SHAP and LIME explanations
- **Notebook:** Explaining black-box models

---

## Course Format and Suggestions

- Each module consists of a brief theoretical overview and one or more interactive notebooks
- Suggested reading or watching links included in markdown cells
- Encourage experimentation: change model parameters, swap datasets
- Tie lessons to broadly applicable datasets and contexts
- Include practical tips for integrating models into applications

---

## Tools and Environment

- Python 3.10+
- Jupyter Notebooks (via Anaconda or JupyterLab)
- IDE (VS Code or similar)
- Git for version control
- Suggested environments: Google Colab, local setup via `venv`, or Docker

---

## Final Project Ideas

- Predict product review ratings from structured data
- Classify user behavior based on web usage logs
- Detect fraudulent transactions
- Estimate customer churn likelihood
