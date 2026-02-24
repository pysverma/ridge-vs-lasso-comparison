# Ridge vs Lasso Regression — Regularization Comparison

This repository compares Ridge and Lasso regression to understand how regularization controls model complexity and prevents overfitting.

---

## What is Regularization?

Regularization adds a penalty term to the loss function to shrink coefficients.

Ridge uses L2 penalty:
Loss = MSE + α * Σ(w²)

Lasso uses L1 penalty:
Loss = MSE + α * Σ(|w|)

---

## Key Differences

- Ridge shrinks coefficients smoothly.
- Lasso can shrink coefficients to exactly zero.
- Lasso performs feature selection.
- Ridge distributes weight across features.

---

## Visualizations Included

- Ridge fit
- Lasso fit
- Coefficient comparison
- Alpha vs coefficient shrinkage
- Alpha vs training/test error

---

## Key Insights

- Increasing alpha increases regularization strength.
- Ridge reduces variance without eliminating features.
- Lasso can eliminate irrelevant features.
- Optimal alpha balances bias and variance.

---

## Tech Stack

- Python
- NumPy
- Matplotlib
- scikit-learn
