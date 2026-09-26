Preprocessing: 

- Notebook: [scripts/preprocessing.ipynb](scripts/preprocessing.ipynb)

Purpose:
This notebook prepares raw client data for modelling by cleaning, encoding categorical variables and splitting into training/testing sets.

Steps performed:
1. Import libraries ('pandas', 'scikit-learn').
2. Load dataset from '../data/Churn_Modelling.csv'.
3. Apply label encoding to categorical features ('Geography', 'Gender').
4. Scale numerical features using 'StandardScaler'.
5. Split dataset into training and testing sets.