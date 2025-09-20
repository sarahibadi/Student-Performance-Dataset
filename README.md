# Student-Performance-Dataset - Linear Regression Assignment CS 4372

- Dataset: Student Performance (Mat)
- Public link: https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student-mat.csv
- Target variable: G3 (final grade)

## How to Run (Colab)
1. Open the notebook in Google Colab.
2. Run all cells top to bottom.
3. Outputs:
   - `sgd_cv_results.csv`: grid-search results for SGDRegressor (hyperparameters + CV scores).
   - `summary_metrics.csv`: side-by-side metrics (R², RMSE, MAE) for SGD and OLS.
   - Plots: distributions, correlation heatmap, residual diagnostics.


## Requirements
- Python 3.9+
- `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `statsmodels`
