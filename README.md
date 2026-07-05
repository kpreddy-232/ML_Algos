# Machine Learning Algorithms from Scratch

This repository contains implementations of core **machine learning** algorithms built completely from scratch in **Python** and **NumPy**.
---

## Overview

The project demonstrates how foundational ML algorithms work under the hood without relying on high-level libraries like `scikit-learn`.  
Each algorithm is written clearly and organized into logical modules for learning, experimentation, and extension.

---

## Structure

```
ML_Algos/
│
├── requirements.txt
└── notebooks/
    │
    ├── ml_algorithms/           # Classical ML implementations
    │   ├── decision_trees.ipynb
    │   ├── k_means.ipynb
    │   ├── lin_reg_GD.ipynb
    │   ├── logistic_reg.ipynb
    │   └── pca.ipynb            # (...and more)
    │
    ├── losses/                  # Loss functions (MSE, Cross-Entropy, etc.)
    ├── metrics/                 # Evaluation metrics (Accuracy, F1 Score, Confusion Matrix, etc.)
    ├── optimizers/              # Optimizers (SGD, Adam, RMSProp, etc.)
    ├── preprocessing/           # Data preprocessing utilities
    └── utils/                   # Helper functions
```

---

## Tech Stack

- **Python 3.10+**
- **NumPy** - mathematical and array operations  
- **Jupyter Notebook** - interactive implementation and visualization  

---

## Features

- From-scratch ML algorithms (no external ML libraries)  
- Well-structured and modular code  
- Educational clarity for ML fundamentals  

---

## Example Topics

- Linear & Logistic Regression  
- Decision Trees  
- K-Means Clustering  
- Principal Component Analysis (PCA)    
- Loss and Metric functions  
- Optimizers and Gradient Computation  

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/kpreddy-232/ML_Algos.git
   cd ML_Algos
   ```

2. **Create a virtual environment and install dependencies**
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Open any notebook under `notebooks/ml_algorithms/` to explore and run the implementations.


---

## ⭐ Acknowledgments

Inspired by core ML theory and Andrew Ng’s ML course.
