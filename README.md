# MMA 865: Global Microfinance Loan Outcome Prediction Challenge

This repository contains the code for the Kaggle competition - **MMA 865: Global Microfinance Loan Outcome Prediction Challenge**.

- **ROC AUC for the submission**: `0.97383`

[Link to the competition](https://www.kaggle.com/competitions/mma-865)

## Python Packages Used

The following Python packages were utilized in this project:

- **Pandas**: Used for data manipulation and analysis.

- **Scikit-Learn**: A machine learning library used for various tasks:
  - `train_test_split`: Splitting data into training and testing sets.
  - `RandomForestClassifier`: Building a random forest classification model.
  - `roc_auc_score`: Evaluating model performance using the ROC AUC metric.
  - `TfidfVectorizer`: Converting text data into TF-IDF features.
  - `OneHotEncoder`: Encoding categorical variables as one-hot arrays.
  - `ColumnTransformer`: Applying different preprocessing steps to different columns.
  - `Pipeline`: Creating a workflow for data preprocessing and model training.
  - `SimpleImputer`: Handling missing data.
  - `FeatureUnion`: Combining multiple feature extraction processes.
  - `BaseEstimator` and `TransformerMixin`: Creating custom transformers.

- **NumPy**: Used for numerical computations and handling arrays.