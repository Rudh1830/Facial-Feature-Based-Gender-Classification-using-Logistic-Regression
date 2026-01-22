# Gender Prediction Using Logistic Regression

This project uses **Logistic Regression** to predict gender based on facial features such as
forehead dimensions, nose shape, lip thickness, and hair length.  
The dataset contains both **binary** and **continuous** features, making Logistic Regression
a suitable and interpretable classification model.

---

## 📊 Dataset Description

The dataset consists of facial attributes extracted from images.

### Features:
| Feature | Type | Description |
|------|------|------|
| long_hair | Binary | 1 = long hair, 0 = short hair |
| forehead_width_cm | Continuous | Width of forehead (cm) |
| forehead_height_cm | Continuous | Height of forehead (cm) |
| nose_wide | Binary | 1 = wide nose |
| nose_long | Binary | 1 = long nose |
| lips_thin | Binary | 1 = thin lips |
| distance_nose_to_lip | Binary | 1 = long distance |
| gender | Target | Male / Female |

---

## 🎯 Objective

To build a **binary classification model** that predicts gender using facial features
and evaluates its performance using standard metrics.

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🧪 Machine Learning Workflow

1. Data loading and inspection
2. Feature–target separation
3. Encoding target variable (Male/Female → 1/0)
4. Train–test split
5. Model training using Logistic Regression
6. Prediction on test data
7. Model evaluation:
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## 🧠 Why Logistic Regression?

- Best suited for binary classification
- Handles mixed feature types well
- Interpretable coefficients
- Strong baseline model
- Efficient and fast to train

---

## 📈 Model Evaluation

The model is evaluated using:
- Accuracy score
- Precision, Recall, F1-score
- Confusion matrix visualization

> Exact results depend on train-test split and random state.

---

🚀 Future Improvements
---

Feature importance visualization

Regularization tuning (L1 / L2)

Cross-validation

Compare with SVM, Random Forest

Deploy as Streamlit app

---
🏷️ Tags
---

Machine Learning Logistic Regression Binary Classification
Gender Prediction Scikit-learn Python
