# Titanic Survival Prediction

This project presents a complete Exploratory Data Analysis (EDA) and Machine Learning (ML) pipeline on the Titanic dataset. It includes data preprocessing, feature selection, dimensionality reduction (PCA), model training using Random Forest, hyperparameter tuning, and comprehensive evaluation.

## Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Description: The dataset contains passenger information such as age, gender, class, fare, and survival status.

## Objectives

- Perform detailed EDA to understand feature distributions and relationships.
- Handle missing values and encode categorical variables.
- Select relevant features using chi-squared test.
- Apply PCA for dimensionality reduction.
- Train and evaluate a classification model using Random Forest.
- Tune hyperparameters using GridSearchCV.
- Assess the model using standard classification metrics.

## Techniques Used

### Exploratory Data Analysis (EDA)

- Countplots, Histograms, Boxplots
- Correlation Heatmap
- Missing Value Visualization
- Outlier Detection

### Data Preprocessing

- Handling missing values
- Label encoding for categorical features
- Feature scaling using Min-Max normalization

### Machine Learning Pipeline

- Feature Selection with SelectKBest (chi2)
- Dimensionality Reduction with PCA
- Model Training using RandomForestClassifier
- Cross-validation with cross_val_score
- Hyperparameter tuning using GridSearchCV

### Model Evaluation

- Confusion Matrix
- Accuracy, Precision, Recall, F1-score
- ROC Curve and AUC Score
