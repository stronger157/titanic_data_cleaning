# titanic_data_cleaning
# 🧼 Data Cleaning & Preprocessing – Titanic Dataset

This repository contains my work on Task 1 of my internship: Data Cleaning and Preprocessing using the Titanic dataset. The goal was to clean raw data, handle missing values, encode categorical variables, scale numerical features, and detect outliers — all essential steps before feeding data into machine learning models.

---

## 📁 Dataset
- Dataset used: **Titanic.csv**
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## ✅ Steps Performed

### 1. Importing the Dataset & Basic Exploration
- Used `pandas` to load the dataset
- Viewed data types, checked null values and basic statistics

### 2. Handling Missing Values
- Filled missing values:
  - `Age`: median
  - `Embarked`: mode
- Dropped columns with too many nulls (like `Cabin` if used)

### 3. Encoding Categorical Features
- Applied:
  - **One-hot encoding** to `Sex` and `Embarked`
  - **Label encoding** to ordered categories (if needed)

### 4. Normalizing / Standardizing Features
- Scaled `Age` and `Fare` using `StandardScaler` from `sklearn`

### 5. Outlier Detection & Removal
- Used boxplots to visualize outliers
- Removed outliers from `Fare` using the IQR method

---

## 📊 Results
- Cleaned and preprocessed dataset is ready for model training
- Missing values handled
- Features are encoded and scaled
- Outliers removed to improve model performance

---

