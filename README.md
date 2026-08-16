# Applied Machine Learning — Coursework

Assignment work from the **Applied Machine Learning** course, worked through on three classic tabular datasets.

## Contents

| File | Topic |
|---|---|
| [`Applied_Machine_Learning_Assignment_1.ipynb`](Applied_Machine_Learning_Assignment_1.ipynb) | Full assignment — preprocessing, model fitting and evaluation |
| [`newfile.py`](newfile.py) | Supporting script |

## Datasets

| File | Task |
|---|---|
| [`adult.csv`](adult.csv) | **Adult / Census Income** — binary classification of income bracket from demographic features |
| [`iris.csv`](iris.csv) | **Iris** — multi-class classification, the standard teaching dataset |
| [`used_cars.csv`](used_cars.csv) | **Used cars** — regression on vehicle price |

Between them these cover the three shapes a tabular problem usually takes: binary classification with heavy categorical features and class imbalance, clean multi-class classification, and continuous regression.

## Topics covered

Data cleaning and missing values · categorical encoding · feature scaling · train/test splitting and cross-validation · classification and regression models · accuracy, precision/recall and error metrics

## Running it

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Applied_Machine_Learning_Assignment_1.ipynb
```
