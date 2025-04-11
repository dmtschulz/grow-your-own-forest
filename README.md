# 🌲 Ensemble Learning from Scratch (Machine Learning 1 Homework)

This project implements decision trees, random forests, and boosting **from scratch**, without relying on `scikit-learn`’s ensemble models. Evaluated on Iris, Bodyfat, and Diabetes datasets, the goal is to explore **bias-variance tradeoffs** and the power of ensembling.

---

## 📦 Features

- Manual implementation of:
  - ✅ Random Forest Classifier (voting)
  - ✅ Random Forest Regressor (averaging)
  - ✅ Boosted Regressor (residual fitting)
- Visualized decision boundaries (Iris)
- Performance benchmarks (R² scores)
- Depth-vs-performance plots for each model

---

## 🖼 Plots

All saved in `/plots/`:
- `random_forest_boundary.png`
- `random_forest_regressor_bodyfat.png`
- `boosted_regressor_diabetes.png`
- `depth_vs_r2_bodyfat.png`
- `depth_vs_r2_diabetes.png`

---

## ⚙️ Stack

- Python  
- NumPy  
- Scikit-learn (for base trees only)  
- Matplotlib  
- Custom `utils.py`

---

## 💡 Note

Everything is implemented manually — no `RandomForestRegressor`, no `GradientBoostingRegressor`. Just loops, lists, and learning the hard way.
