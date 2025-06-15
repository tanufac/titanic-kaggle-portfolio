# Titanic - Kaggle Competition Analysis

This repository contains my solution for the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition on Kaggle.  
I achieved a public leaderboard score of **0.77990** using Random Forest with basic feature engineering.

---

## 🔍 Overview

The goal of this competition is to build a predictive model that answers the question: **“what sorts of people were more likely to survive?”** using passenger data such as age, gender, class, etc.

---

## 📈 Process

1. **Data Cleaning**
   - Handled missing values in `Age`, `Fare`, and `Embarked`
   - Converted categorical variables like `Sex` and `Embarked` to numerical values

2. **Feature Engineering**
   - Extracted `Title` from the `Name` column
   - Created `FamilySize` from `SibSp` + `Parch` + 1
   - Added `IsAlone` as a binary feature

3. **Modeling**
   - Used **Random Forest Classifier** as the main model
   - Compared with Logistic Regression, XGBoost, and LightGBM
   - Performed 5-fold cross-validation to evaluate models

4. **Submission**
   - Generated predictions on the test set and saved them in `submission.csv`

---

## 💡 Key Learnings

- Feature engineering significantly improved performance
- Cross-validation scores may not always align with leaderboard results
- Ensemble methods can improve robustness but may not guarantee higher scores

---

## 📊 Model Performance

| Model              | CV Score | Public LB Score |
|-------------------|----------|-----------------|
| Random Forest      | ~0.78    | **0.77990**     |
| Logistic Regression| ~0.75    | ~0.75           |
| XGBoost            | ~0.76    | ~0.70 (untuned) |
| LightGBM           | ~0.77    | ~0.72 (default) |

---

## 📁 Files

- `titanic_analysis.ipynb`: Main notebook with EDA, feature engineering, and modeling
- `submission.csv`: Prediction file submitted to Kaggle (score: 0.77990)
- `README.md`: This file

---

## 📬 Contact

If you'd like to collaborate or have questions, feel free to reach out via GitHub or LinkedIn.

---
