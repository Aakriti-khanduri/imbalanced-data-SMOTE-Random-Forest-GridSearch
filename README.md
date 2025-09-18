# imbalanced-data-SMOTE-Random-Forest-GridSearch
🚀 Project Overview
In many real-world problems (like churn prediction, fraud detection, medical diagnosis), datasets are often imbalanced — meaning one class heavily outnumbers the other.
This project demonstrates how to handle such datasets effectively using SMOTE (Synthetic Minority Oversampling Technique) and evaluate models with Logistic Regression, SVC, and Random Forest.

⚡ Steps in the Project
Data Preprocessing
Splitting data into training and testing sets.
Using SMOTE to balance the dataset.
Model Training & Evaluation
Compared three models:
Logistic Regression
Support Vector Classifier (SVC)
Random Forest Classifier
Used Cross Validation to check performance.
Hyperparameter Tuning
Applied GridSearchCV on Random Forest.
Tuned parameters:
n_estimators (number of trees)
max_depth
max_features
Final Model
Trained the best Random Forest model with tuned parameters.

🛠️ Tech Stack
Python
Scikit-learn
Imbalanced-learn (SMOTE)
Pandas, NumPy

📈 Results
Logistic Regression, SVC, and Random Forest were compared.
Random Forest (with tuned hyperparameters) performed the best.
SMOTE significantly improved the ability to detect minority class cases.

📂 Files in this Repo
churn_imbalanced.ipynb → Full code with explanation
dataset = Telco_Customer_Churn.csv
requirements.txt → Required Python libraries
README.md → Project overview
