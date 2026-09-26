Model 2: Random Forest

- Notebook: [scripts/model2-random-forest.ipynb](scripts/model2-random-forest.ipynb)

Purpose:
Builds a Random Forest classifier to predict customer churn and evaluates its performance.

Results:
The model was trained and evaluated on the churn dataset.

Key Metrics:
- Accuracy: 0.861
- Precision: 0.784
- Recall: 0.404
- F1 Score: 0.534
- ROC AUC: 0.689 

Classification Report:
| Class        | Precision | Recall | F1 Score | Support |
| 0            | 0.87      | 0.97   | 0.92     | 1607    |
| 1            | 0.78      | 0.40   | 0.53     | 393     |
| Accuracy     |           |        | 0.86     | 2000    |
| Macro Avg    | 0.83      | 0.69   | 0.73     | 2000    |
| Weighted Avg | 0.85      | 0.86   | 0.84     | 2000    |

Confusion Matrix: 
[ 1563 44 ]
[ 234 159 ]

Feature Importances:
Top predictors identified by the Random Forest:
- Age (0.288)
- NumOfProducts (0.210)
- Balance (0.064)
- CreditScore (0.053)

