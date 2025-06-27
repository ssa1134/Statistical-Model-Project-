# 📊 Advertising Sales Prediction with Linear Regression

This project applies *Linear Regression* techniques using both *Statsmodels* and *Scikit-learn* to predict advertising sales based on advertisement budgets across different media: TV, Radio, and Newspaper.

---

## 🔍 Overview

The script reads data from an Advertising.csv file containing historical advertising data. It builds and evaluates regression models using:

- *Statsmodels' OLS* (Ordinary Least Squares)
- *Scikit-learn's LinearRegression*

The performance of both models is compared using *R² score* and *visualizations* of predicted vs actual sales.

---

## 🧾 Dataset

The dataset (Advertising.csv) should be placed in the *same directory* as the script. It should contain the following columns:

- TV: Advertising budget spent on TV
- Radio: Advertising budget spent on Radio
- Newspaper: Advertising budget spent on Newspaper
- Sales: Sales of the product

> ✅ Ensure the file includes the correct headers and is not empty.

---

## ⚙ Setup Instructions

### 1. 🔧 Prerequisites

Ensure Python is installed along with the following libraries:

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels
