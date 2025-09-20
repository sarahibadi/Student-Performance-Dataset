# Student-Performance-Dataset - Linear Regression Assignment CS 4372

- Dataset: Student Performance 
- Source Link: https://archive.ics.uci.edu/dataset/320/student+performance
- Target variable: G3 (final grade)

## How to Run (Colab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sarahibadi/Student-Performance-Dataset/blob/main/linear_regression_assignment.ipynb)

1. Open the notebook in Google Colab.
2. Run all cells top to bottom.
3. Outputs:
   - `sgd_cv_results.csv`: grid-search results for SGDRegressor (hyperparameters + CV scores).
   - `summary_metrics.csv`: side-by-side metrics (R², RMSE, MAE) for SGD and OLS.
   - Plots: distributions, correlation heatmap, residual diagnostics.


## Requirements
- Python 3.9+
- `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `statsmodels`
