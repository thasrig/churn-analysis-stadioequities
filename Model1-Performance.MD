Model 1 Performance: Logistic Regression

- Notebook: [scripts/model1-logistic-regression.ipynb](scripts/model1-logistic-regression.ipynb)

Purpose:
Implements a baseline logistic regression model to predict customer churn.

Results:
The model was trained and evaluated on the churn dataset.

Key Metrics:
- Accuracy: 0.818
- Precision: 0.612
- Recall: 0.201
- F1 Score: 0.303
- ROC AUC: 0.585

Classification:

| Class        | Precision | Recall | F1 Score | Support |
| 0            | 0.83      | 0.97   | 0.90     | 1607    |
| 1            | 0.61      | 0.20   | 0.30     | 393     |
| Accuracy.    |           |        | 0.82     | 2000    |
| Macro Avg    | 0.72      | 0.58   | 0.60     | 2000    |
| Weighted Avg | 0.79.     | 0.82   | 0.78     | 2000    |

Confusion Matrix:
[ 1557 50]
[ 314  79]
