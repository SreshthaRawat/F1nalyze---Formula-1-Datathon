# F1nalyze---Formula-1-Datathon
# Model Training
Two models are trained and evaluated using RandomizedSearchCV for hyperparameter tuning:

XGBoost: An efficient and scalable implementation of gradient boosting.

LightGBM: A gradient boosting framework that uses tree-based learning algorithms and is designed for performance and speed.

# Data Preprocessing Pipeline
A preprocessing pipeline is set up using scikit-learn to handle both numerical and categorical features:

Numerical Features: Imputed using IterativeImputer and scaled using StandardScaler.

Categorical Features: Imputed using SimpleImputer and one-hot encoded using OneHotEncoder.


kaggle notebook
https://www.kaggle.com/code/notbobmarley/notebook520d27abfa
