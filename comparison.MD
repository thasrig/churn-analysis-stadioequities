Model Comparison: Logistic Regression vs Random Forest 

- Logistic Regression Notebook: [scripts/model1-logistic-regression.ipynb](scripts/model1-logistic-regression.ipynb)
- Random Forest Notebook: [scripts/model2-random-forest.ipynb](scripts/model2-random-forest.ipynb)

Performance Metrics:

| Metrics   | Logistic Regression | Random Forest |
| Acuuracy  | 0.818               | 0.861         |
| Precision | 0.612               | 0.784         |
| Recall    | 0.201               | 0.404         |
| F1 Score  | 0.303               | 0.534         |
|ROC AUC    | 0.585               | 0.689         |

Comparison:

Logistic Regression:
Serves as a simple, interpretable baselie. However, the recall is very low (0.20), meaning it misses many churn cases. 

Random Forest:
Achieves higher accuracy, precision, recall, F1 Score and ROC AUC. It captures more churn cases while maintaining strong overall performance. 

In conclusion, Random Forest consistently outperforms Logistic Regression across all key metrics, making it the stronger model for churn prediction in this dataset. 
