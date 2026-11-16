# Machine Learning Assignments

Assignments from **CS-E3210 Machine Learning Basic Principles** at Aalto University (Oct 2018), taught by Prof. Alex Jung.

**Tech stack:** Python · NumPy · pandas · matplotlib · scikit-learn · scipy · Pillow

---

## Assignments

| # | Notebook | Description |
|---|----------|-------------|
| 01 | `1_Introduction.ipynb` | Matrix and vector operations, Matplotlib plotting from scratch, file I/O with NumPy, and eigenvector decomposition. Foundation exercises that underpin every later assignment. |
| 02 | `2_Regression.ipynb` | Linear and polynomial regression implemented from first principles. Gradient descent with learning-rate selection, loss convergence analysis, and performance evaluation on a real dataset. |
| 03 | `3_Classification.ipynb` | k-Nearest Neighbours and decision-tree classifiers applied to tabular and image data. Exploration of decision boundaries, feature spaces, and classifier accuracy. |
| 04 | `4_Model-Validation-and-Selection.ipynb` | Cross-validation and the bias-variance tradeoff applied to cryptocurrency price prediction. Regularization (L1/L2) and model selection across polynomial degrees. |
| 05 | `5_Clustering.ipynb` | Hard clustering with k-Means including local-minima handling, and soft clustering with Gaussian Mixture Models (GMM). Uniform distribution visualization and cluster quality analysis. |
| 06 | `6_Feature-Learning.ipynb` | Principal Component Analysis (PCA) implemented from scratch. Compression-vs-information-loss trade-off study: reconstruction quality as a function of retained principal components. |

---

## Setup

```bash
pip install -r requirements.txt
```

Python 3.8+. `plotchecker` is a course-internal grader — cells that import it can be skipped outside the Aalto course environment.

---

## Data Sources

| File | Used in | Source |
|------|---------|--------|
| `Data.csv`, `DataTask3.csv` | 01_Introduction | Course-provided *(not in repo)* |
| `BTC-USD.csv`, `ETH-USD.csv` | 02_Regression, 04_Model-Selection | [Yahoo Finance](https://finance.yahoo.com) — download via `yfinance` |
| `images/` directory | 03_Classification | Course-provided *(not in repo)* |
| `data.csv` | 05_Clustering | Course-provided *(not in repo)* |
| `fruits/` directory | 06_Feature-Learning | Course-provided *(not in repo)* |