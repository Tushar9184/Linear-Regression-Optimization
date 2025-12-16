# Linear Regression Optimization from Scratch

## 📌 Project Overview

This project implements the **Linear Regression** algorithm using **Gradient Descent** optimization from first principles (Calculus & Linear Algebra). The goal was to mathematically reconstruct the learning process without relying on "Black Box" libraries like `scikit-learn` for the core logic.

## 🔬 Key Features

- **Vectorized Implementation:** Uses NumPy matrix operations (dot products) instead of slow Python loops for performance.
- **Gradient Descent Engine:** Manually calculated partial derivatives for Weight and Bias updates.
- **Comparative Analysis:** Benchmarked accuracy and convergence speed against the industry-standard `sklearn.linear_model`.

## 📊 Results

- **Scikit-Learn MSE:** 437.54
- **My Custom Model MSE:** 436.63
- **Conclusion:** The custom implementation matched (and slightly outperformed) the standard library, verifying the correctness of the mathematical logic.

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** NumPy (Math), Pandas (Data), Matplotlib (Visualization)
