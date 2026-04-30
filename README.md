# 🌍 Global Terrorism Analysis

## 📌 Project Overview

This project analyzes the Global Terrorism dataset to study patterns in terrorist incidents worldwide. The dataset contains detailed information about events including year, country, attack type, target, weapon, and casualties.

The main goal is to perform **data cleaning, exploratory analysis, hypothesis testing, and machine learning modeling** to extract meaningful insights and predict patterns in terrorist activities.

---

## 📌 PROJECT SUMMARY

This project performs Exploratory Data Analysis (EDA) on a dataset containing over **180,000 terrorist incidents (1970–2017)**.

The workflow includes:

* Data preprocessing & cleaning
* Visualization of trends and patterns
* Statistical hypothesis testing
* Machine learning model building

The project aims to transform raw data into **actionable insights for security and policy decision-making**.

---

## 🎯 Objectives

* 📂 Load and inspect dataset
* 🧹 Clean missing and inconsistent data
* ➕ Create new features (casualties, decade, etc.)
* 📊 Perform EDA and visualization
* 🔬 Apply hypothesis testing
* 🤖 Build machine learning models
* 💡 Generate insights for stakeholders

---

## 🛠️ Tools Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 🎨 Seaborn
* 📊 SciPy
* 🤖 Scikit-learn

---

## 🧼 Data Cleaning Steps

* 🗑️ Removed duplicate rows
* ⚠️ Handled missing values
* 🔧 Converted incorrect data types
* ➕ Created `casualties = nkill + nwound`
* 📅 Extracted `year`, `decade`, `month_name`

---

## 📌 Key Columns Used

* 📅 `iyear`
* 🌎 `country_txt`
* 🗺️ `region_txt`
* 🏙️ `city`
* 💣 `attacktype1_txt`
* 🎯 `targtype1_txt`
* 🔫 `weaptype1_txt`
* ☠️ `nkill`
* 🤕 `nwound`
* ✅ `success`
* ⚔️ `suicide`
* 📊 `casualties`

---

## 📊 Exploratory Data Analysis

The analysis includes:

* 📈 Attacks over time
* 🌍 Most affected countries & regions
* 💣 Attack type distribution
* 🎯 Target analysis
* ☠️ Casualty distribution
* 📦 Outlier detection
* 🔥 Correlation heatmap

---

## 📉 Visualizations

1. 📈 Line chart (attacks by year)
2. 📊 Bar chart (top countries)
3. 💣 Attack type frequency
4. 🥧 Target distribution
5. 📉 Casualty histogram
6. 📦 Boxplot (outliers)
7. 🔥 Heatmap

---

# 🔬 Hypothesis Testing

## 📊 Hypothesis 1: Region vs Attack Frequency

* **H₀:** Terrorist attacks are equally distributed across regions
* **H₁:** Terrorist attacks are not equally distributed across regions

👉 **Test Used:** Chi-Square Test

👉 **Insight:**
Shows whether certain regions are significantly more affected than others.

---

## 📊 Hypothesis 2: Attack Type vs Success

* **H₀:** Attack success is independent of attack type
* **H₁:** Attack success depends on attack type

👉 **Test Used:** Chi-Square Test

👉 **Insight:**
Determines if some attack types are more likely to succeed.

---

## 📊 Hypothesis 3: Casualties Relationship

* **H₀:** No correlation between number of killed and wounded
* **H₁:** Significant correlation exists

👉 **Test Used:** Pearson Correlation

👉 **Insight:**
Helps understand whether deadly attacks also tend to injure more people.

---

# 🤖 Machine Learning Implementation

## 🎯 Problem Statements

### 1️⃣ Classification Task

Predict whether an attack is **successful**

* Target: `success`

---

### 2️⃣ Regression Task

Predict **casualties**

* Target: `casualties`

---

## ⚙️ Algorithms Used (6 Models)

### 🔹 1. Logistic Regression

* Used for classification
* Baseline model

---

### 🔹 2. Decision Tree

* Captures non-linear relationships
* Easy to interpret

---

### 🔹 3. Random Forest

* Ensemble method
* High accuracy & robust

---

### 🔹 4. K-Nearest Neighbors (KNN)

* Instance-based learning
* Works on similarity

---

### 🔹 5. Naive Bayes

* Fast and efficient
* Works well with categorical data

---

### 🔹 6. Support Vector Machine

* Used for predicting casualties
* Simple regression baseline

---

## 📊 Model Evaluation

### ✔️ Classification Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### ✔️ Regression Metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 📈 Key ML Insights

* 🌍 Region and attack type strongly influence success
* 💣 Weapon type impacts outcome probability
* ☠️ Casualty prediction is challenging due to outliers
* 🌲 Random Forest gives best classification performance
* 📊 Linear Regression provides baseline for casualty prediction

---

## 👥 Stakeholder Usefulness

* 🏛️ Governments
* 🛡️ Security agencies
* 🎓 Researchers
* 📜 Policy makers
* 🌐 International organizations

---

## 📁 Project Structure

```bash
project-folder/
├── Global_Terrorism_Data.csv
├── notebook.ipynb
├── README.md
└── images/
```

---

## 🚀 How to Run

1. 📥 Clone repository
2. 💻 Open in Jupyter/Colab
3. 📦 Install dependencies
4. ▶️ Run all cells
5. 📊 View insights & models

---

## 🏁 Conclusion

This project demonstrates how **EDA, statistical testing, and machine learning** can be combined to analyze complex real-world data like global terrorism.

It provides valuable insights into patterns, risks, and predictive factors that can support **data-driven decision-making in security and policy planning**.

---

## ✍️ Author

**Adiba Ansari**

---

