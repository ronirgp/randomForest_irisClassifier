# 🌲 Random Forest Iris Classifier

This project demonstrates the use of the **Random Forest Classifier** from `scikit-learn` to classify different species of Iris flowers using the classic **Iris dataset**. The model is trained to predict whether a flower is **Setosa**, **Versicolor**, or **Virginica** based on features like petal and sepal measurements.

---

## 📊 Dataset

- Built-in `load_iris()` dataset from `sklearn.datasets`
- Contains:
  - 150 samples
  - 3 target classes:
    - Setosa
    - Versicolor
    - Virginica
  - 4 numerical features:
    - Sepal length
    - Sepal width
    - Petal length
    - Petal width

---

## 🔍 Goal

Train a machine learning model that can classify a new iris flower based on its measurements. This project demonstrates:
- Data splitting
- Model training
- Accuracy calculation
- Confusion matrix
- Classification report

---

## ✅ Model Used

```python
RandomForestClassifier(n_estimators=100, random_state=42)
