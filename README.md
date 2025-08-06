# 🚢 Titanic Survival Analysis & Prediction

A complete exploratory data analysis (EDA) and machine learning modeling pipeline on the famous Titanic dataset.

## 🎯 Project Goals
- Understand survival patterns based on demographics and ticketing data.
- Engineer meaningful features (e.g., titles, family size, travel alone).
- Visualize distributions, trends, and relationships with survival.
- Handle missing data appropriately using statistical insights.
- Build predictive models and compare their performance.

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 📊 Key EDA Highlights
- Females and children had higher survival rates.
- Passengers in higher classes (1st) and those who paid higher fares were more likely to survive.
- Passengers traveling with family had better survival odds than those alone.
- Port of embarkation influenced survival; Cherbourg had the highest rate.
- Extracted titles from names helped uncover social patterns (e.g., Royalty, Master).
- KDE plots, skewness, and kurtosis were used to assess feature distribution.

## 🔍 Data Preprocessing
- Imputed missing **Age** values using **median** (due to skewed distribution).
- Created new features: `Title`, `AgeGroup`, `IsAlone`, `FamilySize`.
- Cleaned and mapped ticket prefixes.
- Converted suitable categorical variables to `category` dtype.

## 🤖 Model Performance
| Model         | Accuracy  |
|---------------|-----------|
| Random Forest | 82.1% ✅   |
| XGBoost       | 80.0%     |
| SVM (RBF)     | 69.3%     |

Random Forest performed the best in this task.

## 📌 Resources
- [Kaggle Dataset](https://www.kaggle.com/c/titanic/data)

---

Feel free to fork, star ⭐, and explore!
