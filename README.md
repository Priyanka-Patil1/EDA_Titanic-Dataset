# 🚢 Titanic Dataset - Exploratory Data Analysis

This project showcases a complete Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python and visualization libraries like Seaborn and Matplotlib.

---

## 📌 Objectives

- Understand the dataset and clean missing data
- Perform univariate, bivariate, and multivariate analysis
- Engineer new features for better insights
- Visualize key relationships influencing survival
- Summarize insights and next steps

---

## 🧹 Step 1: Data Cleaning

- Dropped 'Cabin' due to excessive missing values
- Filled missing 'Age' using median, 'Embarked' using mode

---

## 📊 Step 2: Univariate Analysis

- **Age**: Most passengers were 20–30 years old. Right-skewed distribution.
- **Fare**: Right-skewed with high-value outliers.
- **Sex**: More males than females onboard.
- **Embarked**: Majority boarded from port S.

---

## 👯‍♀️ Step 3: Bivariate Analysis

- **Sex vs Survived**: Females had a much higher survival rate.
- **Pclass vs Survived**: 1st class passengers were more likely to survive.
- **Embarked vs Survived**: Highest survival from Port C.
- **Fare vs Survived**: Survivors generally paid higher fares.
- **Age vs Survived**: Children had better chances than older adults.

---

## 🛠 Step 4: Feature Engineering

- Created `AgeGroup` with labels: Child, Teen, Young Adult, Adult, Senior
- Clear survival advantage seen for **Children**

---

## 🔁 Step 5: Multivariate Analysis

- Correlation heatmap showed:
  - **Fare** moderately correlates with **Survived** (~0.26)
  - **Pclass** negatively correlates with **Fare** (~ -0.55)
  - **Sex (encoded)** also correlated with survival

---

## 📈 Tools & Libraries

- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 💡 Insights

- 🚺 **Females** and 👶 **Children** had significantly higher survival rates
- 🎩 **1st class passengers** had better odds of survival
- 💰 Higher **fare** linked to better survival chances
- 🧓 **Age** had a slight negative correlation with survival

---

## 🚀 Next Steps

- Encoding categorical variables
- Scaling Fare/Age (if needed)
- Model building (Logistic Regression, Decision Trees, etc.)

---

## 📁 Dataset Source

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

