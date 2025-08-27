# Decision Tree Depth Analysis

This project demonstrates how **Decision Tree Classifiers** perform on synthetic datasets as the **tree depth** changes.  
It shows the effect of **overfitting and underfitting** by comparing training and test accuracy at different maximum depths.

---

## Features
- Generates a synthetic dataset using `make_classification` from scikit-learn.
- Trains **Decision Tree classifiers** with varying `max_depth` values (1–20).
- Calculates and displays **train** and **test accuracy**.
- Visualizes accuracy curves to detect **overfitting** and **underfitting**.

---

## Files
- `decision_tree_depth_analysis.py` → Main script containing the implementation.  
- `README.md` → Documentation for the project.

---

## Requirements
Install dependencies before running:

```bash
pip install scikit-learn matplotlib
