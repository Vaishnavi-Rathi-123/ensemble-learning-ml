# 🚀 Ensemble Learning: From Voting to XGBoost

This repository contains structured implementations of major **Ensemble Learning techniques** in Machine Learning, along with clear intuition and practical experimentation.

The focus is not just on implementation, but on understanding:

- Bias–Variance Tradeoff  
- Model Diversity  
- Sequential vs Parallel Learning  
- Meta-Learning Strategies  

---

## 📌 Topics Covered

### 🔹 1. Voting Ensembles
- Hard Voting
- Soft Voting
- Homogeneous vs Heterogeneous Ensembles

**Core Idea:**  
Combine multiple models to improve stability and reduce variance.

---

### 🔹 2. Boosting Algorithms

Boosting trains models sequentially.  
Each new model focuses on correcting previous errors.

#### ✅ AdaBoost
- Reweights misclassified samples
- Uses weak learners (often shallow trees)
- Focuses more on difficult observations

#### ✅ Gradient Boosting
- Trains new models on residual errors
- Minimizes loss using gradient descent
- Supports both classification and regression

#### ✅ XGBoost
Implemented using the XGBoost library.

Key features:
- Regularization (L1 & L2)
- Parallel computation
- Efficient tree pruning
- Missing value handling
- High performance in structured datasets

---

### 🔹 3. Stacking (Meta Learning)

Implemented using StackingClassifier from scikit-learn.

- Base models generate predictions
- A meta-model learns how to combine them
- Cross-validation used to avoid data leakage

Includes:
- Stacking with cross-validation
- Comparison: Stacking vs Blending
- Meta-feature generation process

---

## 🧠 Key Concepts Explained

- Bias vs Variance
- Why Boosting reduces Bias
- Why Bagging reduces Variance
- Importance of Model Diversity
- Cross-validation in Stacking
- Preventing Data Leakage

---

## 🛠 Implementations Included

- GradientBoostingClassifier  
- GradientBoostingRegressor  
- AdaBoostClassifier  
- XGBClassifier  
- VotingClassifier  
- StackingClassifier  

Each implementation contains:
- Dataset creation / loading
- Model training
- Evaluation metrics
- Structured experimentation

---

## 📊 Learning Outcome

Through this project, I gained practical clarity on:

- When to use Voting vs Boosting vs Stacking  
- Why XGBoost often outperforms traditional boosting  
- How meta-learning improves ensemble robustness  
- Practical differences between Blending and Stacking  

---

## 🎯 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Feature importance comparison
- Model performance benchmarking
- Experiments on real-world datasets

---

## 👩‍💻 Author

Vaishnavi Rathi
