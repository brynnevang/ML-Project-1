# Group 17: Project 1 - Machine Learning Classifiers

Updated 2025-09-30

Ensure to change the file path to your unique path that can access the two provided datasets. 

## Project Outline
1. Preprocessing: handled missing values, encoded categoricals, standardized numerical features (consistent pipeline applied to both training and validation inputs)
2. Perceptron & Adaline: trained baseline models, tracked learning curves (misclassifications for Perceptron, MSE for Adaline), selected best variants by validation CV, and exported predictions.
3. Logistic Regression & SVM: trained scikit‑learn models with standardized inputs, tuned C on a log scale, selected best models, and exported predictions, included a 2‑feature decision‑boundary plot for comparison.
4. Reflection: addressed scaling importance, batch vs. SGD, why sklearn outperforms simple book code, boundary differences, the role of regularization, and sensitivity to C values

## Reproduce Predictions
1. Create/activate a Python environment and install: `pandas`, `numpy`, `scikit-learn`, `matplotlib` 
2. Run the notebook `Group_17_Project_1.ipynb`, this will write the four CSV outputs
3. Ensure the validation input file is present and correctly referenced in the notebook

## CSV notes on layout for readability and grading
Group_17_Perceptron_PredictedOutputs.csv
- Rows: 6513, Columns: 1, Column name: prediction
Preview (first 3 rows):
```json
{
  "prediction": [
    "<=50K",
    "<=50K",
    "<=50K"
  ]
}
```

Group_17_Adaline_PredictedOutputs.csv
- Rows: 6513 Columns: 1, Column name: prediction
Preview (first 3 rows):
```json
{
  "prediction": [
    "<=50K",
    "<=50K",
    ">50K"
  ]
}
```

Group_17_LogisticRegression_PredictedOutputs.csv
- Rows: 6513, Column: 1, Column name: prediction
Preview (first 3 rows):
```json
{
  "prediction": [
    "<=50K",
    "<=50K",
    ">50K"
  ]
}
```

Group_17_SVM_PredictedOutputs.csv
- Rows: 6513, Column: 1, Column name: prediction
Preview (first 3 rows):
```json
{
  "prediction": [
    "<=50K",
    "<=50K",
    ">50K"
  ]
}
