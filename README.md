This repo contains code for Kaggle competiton - MMA 865: Global Microfinance Loan Outcome Prediction Challenge

ROC AUC for the submission was: 0.97383

Link to the competition: https://www.kaggle.com/competitions/mma-865

## Python Packages Used

The following Python packages were utilized in this project:

- **Pandas**: Used for data manipulation and analysis.
- **Scikit-Learn**: A machine learning library used for various purposes:
  - `train_test_split` for splitting data into training and testing sets.
  - `RandomForestClassifier` for building a random forest classification model.
  - `roc_auc_score` for evaluating model performance using the ROC AUC metric.
  - `TfidfVectorizer` for converting text data into TF-IDF features.
  - `OneHotEncoder` for encoding categorical variables as one-hot arrays.
  - `ColumnTransformer` for applying different preprocessing steps to different columns.
  - `Pipeline` for creating a workflow of data preprocessing and model training.
  - `SimpleImputer` for handling missing data.
  - `FeatureUnion` for combining multiple feature extraction processes.
  - `BaseEstimator` and `TransformerMixin` for creating custom transformers.
- **NumPy**: Used for numerical computations and handling arrays.
