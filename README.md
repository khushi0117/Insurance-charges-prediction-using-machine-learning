# 🏥 Insurance Charges Prediction - Machine Learning Project

## 📌 Project Overview
This project aims to build a **supervised machine learning** model to **predict insurance charges** based on demographic and health-related features such as:
- Age  
- Sex  
- BMI  
- Number of children  
- Smoker status  
- Region  

The model uses a **Linear Regression** approach to estimate charges, helping stakeholders understand **cost drivers** and make **data-driven decisions**.

---

## 📂 Dataset
The dataset used is **`insurance.csv`** which contains **1,338 records** with the following features:

| Feature            | Description |
|--------------------|-------------|
| `age`              | Age of the individual |
| `sex`              | Gender (`male`, `female`) |
| `bmi`              | Body Mass Index |
| `children`         | Number of children/dependents |
| `smoker`           | Smoking status (`yes`, `no`) |
| `region`           | Residential region in the U.S. (`northeast`, `northwest`, `southeast`, `southwest`) |
| `charges` *(target)* | Individual medical costs billed by health insurance |

---

## 🔍 Project Steps

### 1️⃣ Data Loading and Exploration
- Loaded dataset & checked structure/statistics  
- Verified missing values and data types

### 2️⃣ Data Preprocessing
- Encoded categorical variables (`sex`, `smoker`) into binary numeric form  
- Created dummy variables for `region`  
- Categorized `bmi` into groups (`Normal`, `Overweight`, `Obese`)

### 3️⃣ Feature Engineering & Analysis
- Scaled numerical features  
- Performed **correlation analysis**  
- Used **Chi-square tests** to identify significant categorical features

### 4️⃣ Model Building
- Built **Linear Regression** model with selected features  
- Trained model and evaluated predictions

---

## 🛠 Tools & Libraries
- **Python 3**
- **Pandas**, **NumPy** → Data manipulation  
- **Seaborn**, **Matplotlib** → Visualization  
- **Scikit-learn** → Machine learning modeling

