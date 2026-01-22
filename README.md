# SharkBite_datasci1
Exploring factors and machine learning analysis that are associated with shark attack injury severity. 

## Full Report

[VIEW CANVA REPORT]
(https://www.canva.com/design/DAG-csxtMQg/1A4586YIr2FT2D6yIRoaqg/edit?utm_content=DAG-csxtMQg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

# Project Overview
The goal is to identify and understand features linked to the severities of injuries caused by shark attacks. 

Both statistical methods and machine learning models are used.

# Research Question
- Which features are most strongly associated with fatal shark attacks?
- How victim, location, and activity characteristics influency injury severity?
- How does injury severity change overtime?
- How does class imbalance affect interpretations of model results?

# Methods
- Data cleaning + feature engineering
- Encoding Categorical Features
- Handling class imbalance
- Statistical analysis:
  - Mann–Whitney U test
- Machine learning models:
  - Logistic Regression
  - XGBoost
- Model Optimisations :
  - Hyperparameter tuning with cross validation
  - Handling class imbalance with class weights
  - Decision Threshold Tuning to balance precision-recall tradeoffs
- Model interpretation:
  - Coefficient magnitude (Logistic Regression)
  - Feature importance analysis
- Evaluation metrics:
  - ROC-AUC
  - PR-AUC
  - Precision, Recall, F1-score
  - Confusion matrices
 
# Key Findings
Certain activities and locations are strongly associated with fatal outcomes. Class imbalance strongly influences model performance. While recall for fatal cases remains limited due to severe class imbalance, the final model was selected to preserve reliable performance across non-fatal classes. This reflects a deliberate trade-off between maximizing fatal-case recall and maintaining stable, interpretable predictions for the majority of observations.

# Tools and Libraries
- Python
- Pandas, NumPy
- scikit-learn
- XGBoost
- matplotlib/seaborn

# Files
- shark.ipynb - main notebook
- README.md - documentation
- shark.xlsx - dataset

# Author
Evelane
Bachelor of IT ( Data Science ), MQU
