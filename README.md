# CodSoft Data Science Internship Tasks

This repository contains projects completed as part of my CodSoft Data Science Internship.

---

# Task 1 — Titanic Survival Prediction 🚢

## Project Overview

Built a Machine Learning model to predict whether a Titanic passenger survived or not based on passenger information.

### Algorithm Used
- Logistic Regression

### Key Steps
- Data exploration
- Missing value handling
- Data preprocessing
- Exploratory Data Analysis
- Feature encoding
- Train-test split
- Model training
- Prediction
- Model evaluation

### Model Performance

**Accuracy: 81.01%**

The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# Task 3 — Iris Flower Classification 🌸

## Project Overview

This project uses the Iris dataset to classify flowers into three species:

- Setosa
- Versicolor
- Virginica

The classification is based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Objective

The objective is to build a Machine Learning classification model that can identify the species of an Iris flower based on its measurements.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset

The Iris dataset contains **150 samples** with **4 features**.

Each sample belongs to one of three species:

- Setosa
- Versicolor
- Virginica

## Exploratory Data Analysis

The project includes visualizations such as:

- Species distribution
- Sepal Length vs Sepal Width
- Petal Length vs Petal Width

### Key Observations

- Setosa is clearly separated from the other species.
- Versicolor and Virginica have some overlap.
- Petal length and petal width provide strong separation between the species.

## Machine Learning Model

### Logistic Regression

Logistic Regression was used as the classification algorithm.

The dataset was divided into:

- **80% Training Data**
- **20% Testing Data**

The model was trained using 120 samples and evaluated using 30 test samples.

## Model Performance

### Accuracy

**96.67%**

### Classification Report

| Species | Precision | Recall | F1-Score |
|---------|-----------|--------|----------|
| Setosa | 1.00 | 1.00 | 1.00 |
| Versicolor | 1.00 | 0.90 | 0.95 |
| Virginica | 0.91 | 1.00 | 0.95 |
| **Overall** | **0.97** | **0.97** | **0.97** |

## Confusion Matrix

The model correctly classified:

- 10 Setosa flowers
- 9 Versicolor flowers
- 10 Virginica flowers

Only **1 Versicolor flower was incorrectly classified as Virginica**.

Therefore:

**29 out of 30 test samples were classified correctly.**

## Sample Prediction

A new flower was provided to the trained model with the following measurements:

- Sepal Length: 5.1 cm
- Sepal Width: 3.5 cm
- Petal Length: 1.4 cm
- Petal Width: 0.2 cm

### Prediction

**Setosa**

## Conclusion

The Logistic Regression model successfully classified Iris flowers into Setosa, Versicolor, and Virginica species.

The model achieved an accuracy of **96.67%** on the test dataset, demonstrating strong classification performance.

---

---

# Task 4 — Sales Prediction Using Python 📈

## Project Overview

This project uses Machine Learning to predict product sales based on advertising expenditure across three platforms:

- TV
- Radio
- Newspaper

The target variable is **Sales**.

## Objective

The objective is to build a regression model that can learn the relationship between advertising expenditure and sales and predict expected sales for a given advertising budget.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset

The dataset contains **200 records** with the following variables:

| Feature | Description |
|---------|-------------|
| TV | Advertising expenditure on TV |
| Radio | Advertising expenditure on Radio |
| Newspaper | Advertising expenditure on Newspaper |
| Sales | Product sales |

## Exploratory Data Analysis

The project includes visualizations for:

- TV Advertising vs Sales
- Radio Advertising vs Sales
- Newspaper Advertising vs Sales
- Correlation Matrix

### Key Observations

- TV advertising shows a clear positive relationship with sales.
- Radio advertising also shows a positive relationship with sales.
- Newspaper advertising has a comparatively weaker relationship with sales.

## Machine Learning Model

### Linear Regression

Linear Regression was used to predict sales from the advertising expenditure features.

The dataset was divided into:

- **80% Training Data**
- **20% Testing Data**

The model was trained using 160 samples and evaluated using 40 test samples.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Sample Prediction

A new advertising budget was provided to the trained model:

- TV: 150
- Radio: 25
- Newspaper: 20

### Prediction

**Predicted Sales: 14.47 units**

## Conclusion

A Linear Regression model was successfully developed to predict sales based on advertising expenditure.

The project demonstrates a complete Machine Learning regression workflow, including data exploration, visualization, feature selection, model training, evaluation, and prediction.

For the given advertising budget of TV = 150, Radio = 25, and Newspaper = 20, the model predicted approximately **14.47 units of sales**.

---

## Project Structure

```text
CODSOFT_TASKS1/
│
├── TASK1/
│   └── Titanic_Survival_Prediction.ipynb
│
├── TASK3/
│   └── Iris_Flower_Classification.ipynb
│
├── TASK4/
│   └── Sales_Prediction.ipynb
│
└── README.md
