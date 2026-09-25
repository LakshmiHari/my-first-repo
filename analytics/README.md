pip install -r requirements.txt
01_eda.ipynb
02_modeling.ipynb

EDA Decisions:

Missing-value handling strategy (with percentages),  Outlier detection using IQR, Skewness analysis for fare, Survival breakdown by sex, pclass, and both combined.

Modeling Decisions:

Stratified split justification, Preprocessing pipeline (imputer, encoder, scaler), Classifiers used: Logistic Regression, Decision Tree, Random Forest., Imbalance handling (baseline vs balanced weights vs SMOTE), Hyperparameter tuning for Random Forest, Regression side-task for fare prediction.

Outputs:

Comparison table of metrics (classification + regression separately).
