# 🚀 Spaceship Titanic — Classification

Solutions to two classic Kaggle classification challenges:
- [**Spaceship Titanic**](https://www.kaggle.com/competitions/spaceship-titanic) — predict which passengers were transported to an alternate dimension
- [**Titanic**](https://www.kaggle.com/competitions/titanic) — the original survival-prediction problem

## Overview
| Notebook | Problem |
|---|---|
| `spaceship-titanic.ipynb` | Spaceship Titanic — binary classification on passenger/cabin/spend features |
| `titanic.ipynb` | Titanic — survival classification |

## Techniques
- **EDA** — missing-value analysis, categorical breakdowns, target relationships
- **Feature engineering** — splitting composite fields (cabin deck/side, passenger group), imputation, spend aggregations
- **Modeling** — Logistic Regression, Random Forest, gradient boosting; cross-validated
- **Evaluation** — accuracy, confusion matrix, submission generation

## Run it
```bash
pip install -r requirements.txt
# Download data from the Kaggle competition pages into ./data
jupyter notebook spaceship-titanic.ipynb
```

> Competition data is **not** committed — download from Kaggle.

## Author
**Vamshi Krishna Damidi** — Data & AI Engineer
🌐 [Portfolio](https://vkdvamshi.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/vamshi-krishna-damidi-b6434512/) · 🐙 [GitHub](https://github.com/vkdvamshi)
