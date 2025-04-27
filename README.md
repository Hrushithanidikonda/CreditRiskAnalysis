# Credit Risk Analysis Using Machine Learning

## Project Overview
This project focuses on predicting customer credit card defaults using supervised machine learning algorithms.  
It uses the Taiwan Credit Card Default dataset and applies Logistic Regression, Random Forest, Naïve Bayes, and XGBoost models.

## Models Applied
- Logistic Regression
- Random Forest
- Naïve Bayes
- XGBoost

##  Key Techniques
- Feature scaling using StandardScaler
- SMOTE for class imbalance handling
- Cross-validation and hyperparameter tuning
- Model evaluation using Accuracy, F1-Score, ROC-AUC

## Best Model
- **XGBoost** achieved highest performance:
  - Accuracy: 79.33%
  - ROC-AUC Score: 87.12%
  - F1-Score: 77.70%

## Visual Outputs
- Confusion Matrices
- ROC Curves
- SHAP Summary Plots
- LIME Interpretability Explanations

##  Ethical Considerations
- Ensured explainability and fairness
- Applied SHAP and LIME for model interpretability
- Maintained responsible AI practices

## Project Structure
Credit-Risk-Analysis/
│
├── CreditRiskModel.ipynb        
├── creditriskmodel.py          
├── README.md                   
├── LICENSE                      
└── figures/                     
