# Diabetes Disease Prediction 🩺

A binary classification Machine Learning project to predict whether a patient is diabetic or non-diabetic based on clinical features, using the PIMA Indians Diabetes Dataset.

---

## 📁 Project Structure

```
Diabetes-Prediction-using-Machine-Learning/
├── Diabetes Prediction using Support Vector Machines.ipynb  # Main Notebook
├── diabetesdata.csv                                         # Dataset
├── LICENSE
└── README.md
```

---

## 📊 Dataset

- **Source:** PIMA Indians Diabetes Dataset
- **Records:** 768 patients
- **Features:** 8 clinical features
  - Pregnancies, Glucose, BloodPressure, SkinThickness
  - Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target:** Outcome (1 = Diabetic, 0 = Non-Diabetic)
- **Class Distribution:** 65% Non-Diabetic, 35% Diabetic

---

## 🤖 Models Used

| Model | Test Accuracy |
|---|---|
| Logistic Regression | 81.17% |
| SVM (Linear Kernel) | 80.52% |

✅ **Best Model:** Logistic Regression with **81.17% test accuracy** and **84% precision**

---

## ✨ Key Features

- **StandardScaler** normalization for feature scaling
- **Stratified train-test split (80/20)** for balanced evaluation
- **Model benchmarking** — Logistic Regression vs SVM
- **Real-time prediction pipeline** accepting patient clinical inputs

---

## 🛠️ Tools Used

- **Python** — Core programming language
- **Scikit-learn** — ML models and preprocessing
- **Pandas & NumPy** — Data manipulation
- **Jupyter Notebook** — Development environment

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Harris-Majeed/Diabetes-Prediction-using-Machine-Learning.git
   ```
2. Install dependencies:
   ```bash
   pip install scikit-learn pandas numpy
   ```
3. Open the notebook and run all cells

---

## 📬 Contact

Haris Majeed — [harismajeed299@gmail.com](mailto:harismajeed299@gmail.com)

> For More Projects: [**Follow me on GitHub**](https://github.com/Harris-Majeed)
