# 🚢 Titanic Dataset Exploratory Data Analysis

## 📌 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of the Titanic dataset obtained from Kaggle. Using Python and data visualization techniques, the analysis aims to uncover patterns, trends, and relationships that influenced passenger survival during the Titanic disaster.

The project demonstrates the complete EDA workflow, including data understanding, data cleaning, univariate analysis, bivariate analysis, and insight generation.

---

## 🎯 Objectives

* Understand the structure and characteristics of the Titanic dataset.
* Identify and handle missing values appropriately.
* Perform univariate and bivariate analyses using visualizations.
* Explore relationships between passenger characteristics and survival outcomes.
* Generate meaningful insights from historical passenger data.

---

## 🛠️ Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Dataset Information

* **Dataset:** Titanic Dataset (Kaggle)
* **Total Records:** 891 passengers
* **Total Features:** 12 columns

### Features Included

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Imputed missing values in the **Age** column using the median.
* Filled missing values in the **Embarked** column using the mode.
* Retained the **Cabin** column despite extensive missing values to preserve dataset integrity.
* Checked for duplicate records.
* Verified data types and dataset consistency.

## 🔍 Key Findings

* Female passengers exhibited significantly higher survival rates than male passengers.
* First-class passengers had substantially better chances of survival.
* Third-class passengers experienced the highest number of fatalities.
* Most passengers were young and middle-aged adults.
* Ticket fares were highly right-skewed, with a small number of passengers paying exceptionally high fares.
* Higher ticket fares were generally associated with improved survival outcomes.
* Socioeconomic status played an important role in determining survival.
* Age showed only a weak relationship with survival.
* Statistical outliers represented genuine passenger characteristics and were retained during analysis.


## 📄 Project Report

A detailed PDF report summarizing the methodology, visualizations, findings, and conclusions is included in this repository:

**Titanic_EDA_Report.pdf**

---

## 👨‍💻 Author

**Sajja Yasodha Krishna**

This project was completed as part of an internship assignment to demonstrate practical skills in exploratory data analysis, data visualization, and analytical storytelling using Python.

