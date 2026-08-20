# Titanic Survival Prediction 🚢

## CodSoft Data Science Internship — Task 1

### 📌 Project Overview

This project focuses on building a Machine Learning model to predict whether a passenger on the Titanic survived or not.

The project follows a complete Machine Learning workflow including data exploration, data cleaning, exploratory data analysis, preprocessing, model training, prediction, and evaluation.

---

## 🎯 Objective

The objective of this project is to develop a classification model that predicts passenger survival based on features such as:

- Passenger Class
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Port of Embarkation

### Target Variable

- `0` → Did Not Survive
- `1` → Survived

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## 📊 Dataset

The Titanic dataset contains information about individual passengers, including their age, gender, passenger class, fare, and survival status.

The dataset was loaded and analyzed using Pandas.

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

1. Checked the dataset structure and statistics.
2. Identified missing values.
3. Removed the `Cabin` column due to a large number of missing values.
4. Filled missing `Age` values using the median.
5. Filled missing `Embarked` values using the most frequent value.
6. Removed unnecessary columns:
   - `PassengerId`
   - `Name`
   - `Ticket`
7. Converted categorical variables using one-hot encoding.
8. Split the dataset into training and testing sets using an 80:20 ratio.

---

## 📈 Exploratory Data Analysis

The following visualizations were performed:

- Overall Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Age vs Survival

### Key Observations

- Female passengers had a higher survival count compared with male passengers.
- First-class passengers had better survival outcomes compared with third-class passengers.
- Most passengers were concentrated around the 20–35 age range.

---

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression was used because Titanic survival prediction is a binary classification problem.

The model was trained using 80% of the dataset and evaluated using the remaining 20%.

---

## 📊 Model Performance

### Accuracy

**81.01%**

### Classification Report

| Class | Precision | Recall | F1-Score |
|------|-----------|--------|----------|
| 0 — Not Survived | 0.83 | 0.86 | 0.84 |
| 1 — Survived | 0.79 | 0.74 | 0.76 |
| **Overall** | **0.81** | **0.81** | **0.81** |

### Confusion Matrix

The model correctly classified:

- 90 passengers as Not Survived
- 55 passengers as Survived

It incorrectly classified:

- 15 passengers as Survived
- 19 passengers as Not Survived

---

## 🔮 Sample Prediction

A sample passenger was provided to the trained model for prediction.

### Result

**Passenger was predicted to SURVIVE.**

---

## 📁 Project Structure

```text
CODSOFT_TASKS1/
│
├── TASK1/
│   └── Titanic_Survival_Prediction.ipynb
│
└── README.md
