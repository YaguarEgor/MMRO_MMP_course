# MMRO / MMP Course — Machine Learning Practice

This repository contains solved practical assignments from the **Mathematical Methods of Object Recognition** course, completed as part of the **MMP program at CMC MSU**.

The main goal of the repository is to collect hands-on machine learning notebooks that combine theory, implementation, experiments, and analysis in Python.

---

## Repository Overview

Each directory corresponds to a separate practical assignment from the course. The notebooks cover different parts of the classical machine learning pipeline: data preprocessing, exploratory data analysis, linear models, support vector machines, regularization, model evaluation, and gradient boosting.

```text
MMRO_MMP_course/
│
├── mmro_1_numpy_pandas/
│   └── numpy_pandas_matplotlib_2025.ipynb
│
├── mmro_2_linregr/
│   └── homework_practice_02_linregr.ipynb
│
├── mmro_3_svm_linreg/
│   └── hw_mmro_practice_3_svm_linreg.ipynb
│
├── mmro_4_gb/
│   ├── hw_practice_4.ipynb
│   └── catboost_info/
│
└── README.md
```

---

## Topics Covered

### 1. NumPy, pandas and Matplotlib

The first notebook focuses on the basic Python tools used in data analysis and machine learning:

* working with arrays using **NumPy**;
* processing tabular data with **pandas**;
* basic data visualization with **Matplotlib**;
* simple exploratory analysis;
* practical work with real datasets.

This part serves as a foundation for the later machine learning assignments.

---

### 2. Exploratory Data Analysis and Linear Regression

The second notebook is dedicated to the full workflow of a regression task:

* exploratory data analysis;
* feature preprocessing and feature engineering;
* training linear regression models;
* evaluating prediction quality;
* interpreting model behavior.

The assignment demonstrates how raw data can be transformed into useful features and how classical linear models can be applied to real-world prediction problems.

---

### 3. Linear Models and Support Vector Machines

The third notebook explores classification models and their comparison:

* linear classification methods;
* support vector machines;
* kernel methods;
* hyperparameter tuning;
* quality metrics such as accuracy, ROC-AUC and PR-AUC;
* comparison of different model configurations.

This part shows how model choice, feature scaling, kernels and regularization influence classification performance.

---

### 4. Bias-Variance Decomposition and Gradient Boosting

The fourth notebook studies ensemble methods and model complexity:

* bias-variance decomposition;
* decision trees as base models;
* gradient boosting;
* practical implementation and experiments;
* model evaluation on tabular data;
* use of boosting libraries such as CatBoost.

This assignment highlights the difference between simple models and powerful ensemble methods, especially on structured datasets.

---

## Technologies Used

The repository is based on the standard Python machine learning stack:

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **pandas**
* **Matplotlib**
* **Seaborn**
* **scikit-learn**
* **CatBoost**

Some notebooks may also use additional libraries for visualization or dataset-specific processing.

---

## Purpose of the Repository

This repository is mainly intended as a personal collection of solved course assignments and practical machine learning experiments.

It can be useful for:

* reviewing classical machine learning methods;
* studying examples of applied data analysis in Python;
* comparing different ML models on practical tasks;
* refreshing course material before exams or interviews;
* tracking progress through the MMRO course.
