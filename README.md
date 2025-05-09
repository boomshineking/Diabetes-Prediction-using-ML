# 🩺 Diabetes Prediction using Machine Learning

This project predicts whether a person is diabetic or not based on health metrics using supervised learning techniques.

## 📊 Problem Statement
To build a classification model that can predict diabetes based on several medical predictors from the PIMA Indians Diabetes dataset.

## 📁 Dataset
- **Source:** [Kaggle - Diabetes Dataset](https://www.kaggle.com/johndasilva/diabetes)
- **Features:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (Random Forest, Logistic Regression, SVM, Decision Trees)
- Matplotlib, Seaborn

## ⚙️ Steps Involved
1. Data loading and preprocessing (handling missing values)
2. Exploratory Data Analysis (EDA) and visualization
3. Feature scaling using `StandardScaler`
4. Model comparison using `GridSearchCV` and `ShuffleSplit`
5. Model evaluation using confusion matrix and classification report
6. Predictive function for user inputs

## ✅ Model Performance
- Best model: **Random Forest Classifier**
- Accuracy on test set: ~94.8%
- Included evaluation for both test and training datasets

## 🔮 Prediction Example
```python
predict_diabetes(2, 81, 72, 15, 76, 30.1, 0.547, 25)
