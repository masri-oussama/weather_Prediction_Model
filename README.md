# weather_Prediction_Model

This project builds a complete machine learning pipeline to predict whether it will **rain today** in Australia, using the well-known Australian weather dataset.

The main target variable is:

- `RainToday` → **Yes / No**

The project was originally developed inside an IBM Skills Network lab, then cleaned and refactored into a GitHub-friendly notebook.

---

## 🔍 Project Overview

The notebook walks through a full supervised learning workflow:

1. **Data loading & cleaning**
2. **Exploratory data analysis (EDA)**
3. **Feature engineering**
   - Extract a `Season` feature from the `Date` column
4. **Train / test split with stratification**
5. **Preprocessing pipelines**
   - Scale numeric features with `StandardScaler`
   - One-hot encode categorical features with `OneHotEncoder`
6. **Modeling**
   - `RandomForestClassifier`
   - `LogisticRegression`
7. **Hyperparameter tuning**
   - `GridSearchCV` with cross-validation
8. **Evaluation**
   - Accuracy
   - Classification report (precision, recall, F1-score)
   - Confusion matrix
9. **Model comparison**
   - Random Forest vs Logistic Regression
   - Impact of class imbalance on performance
