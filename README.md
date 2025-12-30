# Titanic Survival Prediction - Machine Learning Project

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using real historical data and machine learning techniques.  
The purpose is to demonstrate data preprocessing, feature engineering, model selection, and evaluation, similar to workflows used in healthcare AI problems.

---

## 🧠 Project Goals
- Load and explore the Titanic dataset
- Clean and preprocess data (handle missing values, encode features)
- Engineer additional features (e.g., FamilySize, IsAlone)
- Compare multiple machine learning models
- Use cross-validation and hyperparameter tuning
- Evaluate the best model using metrics relevant to classification

---

## 🚀 Final Model
The best performing model is a tuned **Random Forest Classifier** with:
- `max_depth = 10`
- `n_estimators = 50`

This model achieved:
- **Accuracy:** ~0.83 (cross-validation)
- **ROC-AUC:** ~0.986
- **Precision & Recall:** strong balance for both classes

---

## 🧩 How to Use This Project

1. Clone the repository
   git clone https://github.com/Naresh7093/Titanic-Survival-ML-Project

2. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib

3. Open the notebook inside the `notebook/` folder and run all cells.

## 📁 Project Structure

├── models/
│   └── titanic_survival_model.joblib   (to be added soon)
├── notebook/
│   └── Titanic_Survival_Model.ipynb
└── README.md

## 👨‍💻 Author
**Naresh Tallapaka**  
Aspiring Machine Learning Engineer with interest in healthcare AI and survival prediction models.

---
