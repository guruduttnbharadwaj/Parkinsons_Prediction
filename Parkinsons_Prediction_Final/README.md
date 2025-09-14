# Parkinson's Disease Prediction

This project uses machine learning algorithms (Logistic Regression, Random Forest, Decision Tree, Naive Bayes, KNN, SVM) 
to predict Parkinson's disease from voice measurements.

## Dataset
- `data/parkinsons.xl.xlsx` : 197 samples, 23 attributes
- `data/ParkinsonNames.txt` : dataset description

## Installation
```bash
pip install -r requirements.txt
```

## Usage
Open the notebook and run:
```bash
jupyter notebook "Project 1.ipynb"
```

## Output
- Accuracy and reports for multiple ML models
- Best performing model can be saved as `deploy_SVM.pkl`
