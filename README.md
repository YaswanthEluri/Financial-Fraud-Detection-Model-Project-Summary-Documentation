# Financial-Fraud-Detection-Model-Project-Summary-Documentation
The Financial Fraud Detection Model aims to identify fraudulent transactions in financial datasets using machine learning and data analytics. This system helps banks, fintech companies, and financial institutions detect suspicious activities early to reduce financial losses and risks.
Project Phases
Phase 1: Data Preprocessing
Collected transaction data (CSV).
Handled missing values, normalized amounts.
Performed feature engineering:
Calculated deltas in balances.
Encoded transaction types.
Removed identifier columns like names.

Phase 2: Model Building
Applied various models including:
Logistic Regression, Random Forest, XGBoost
Chose XGBoost for its high performance.
Split data into training/testing.
Trained model and saved it as model.pkl.

🧠 Tech Stack: 
Python
XGBoost (for classification)
Pandas, Scikit-learn (for data handling and preprocessing)
Joblib (for model serialization)
