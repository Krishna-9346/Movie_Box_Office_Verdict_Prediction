# 🎬 Movie Box Office Verdict Prediction

This project predicts whether a movie will be a **Blockbuster**, **Hit**, **Average**, or **Flop** based on features like cast, genre, and budget. It applies data preprocessing, feature engineering, and machine learning to solve a real-world classification problem.

---

## 📊 Problem Statement

Given various attributes of a movie (e.g., cast, genre, runtime, budget), predict the box office outcome:
- **Blockbuster**
- **Hit**
- **Average**
- **Flop**

---

## 📁 Dataset Features

- `Genre`, `Director`, `Lead Actor`, `Supporting Actor`
- `Budget`, `Runtime`, `Language`
- `Gross Revenue` (used to create target labels)
- Custom label encoding: Flop / Average / Hit / Blockbuster

---

## 🧪 Approach

- Cleaned and preprocessed missing values and outliers
- Engineered the target label from revenue data using domain logic
- Applied encoding using `ColumnTransformer` + `OneHotEncoder`
- Split data into training and test sets
- Trained a `RandomForestClassifier`
- Tuned hyperparameters using `GridSearchCV` and `5-Fold Cross-Validation`

---

## 📈 Evaluation

- Accuracy: **96% on test data**
- Evaluation: Classification Report, Cross-validation scores
- Visualized confusion matrix and important features

---

## 🛠 Tech Stack

- Python, pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository or open in Google Colab
2. Run each cell step-by-step
3. Change movie feature values to test predictions

---

✅ Built by G. Krishna Sumasree – Passionate about real-world ML projects
