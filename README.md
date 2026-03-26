
---

# 🚗 Road Accident Risk Prediction (Regression Model)

This repository contains my work for a **Kaggle competition** focused on predicting **road accident risk using a regression model**.

The goal is to estimate a **continuous risk score** based on structured features derived from a simulated road accident dataset.

---

## 🎯 Objective

The task is to build a **regression model** that can accurately predict the **risk level of road accidents**.

Unlike a classification problem, the output is a **continuous value representing accident risk intensity**.

---

## 📊 Dataset Description

The dataset provided for this competition (train and test sets) was generated using a **deep learning model trained on the Simulated Roads Accident dataset**.

* The feature distributions are **similar but not identical** to the original dataset.
* Participants are allowed to use the **original Simulated Roads Accident dataset** to:

  * Explore distribution differences
  * Improve model performance
  * Enhance feature engineering strategies

---

## 📁 Repository Structure

```
├── main_code.ipynb   # Full pipeline: EDA, preprocessing, modeling, evaluation
├── test.csv          # Test dataset used for predictions
```

---

## 🔍 Project Workflow

The notebook (`main_code.ipynb`) includes the full machine learning pipeline:

### 1. Exploratory Data Analysis (EDA)

* Understanding feature distributions
* Identifying correlations between variables
* Detecting missing values and anomalies

### 2. Data Preprocessing

* Cleaning and preparing data for modeling
* Feature scaling and normalization

### 3. Feature Engineering

* Creating and selecting relevant predictive features
* Comparing synthetic vs original dataset distributions (if applicable)

### 4. Model Building

* Training regression models such as:

  * Linear Regression
  * Random Forest Regressor
  * Gradient Boosting models

### 5. Evaluation

* Model performance measured using regression metrics such as:

  * RMSE (Root Mean Squared Error)
  * MAE (Mean Absolute Error)
  * R² Score

### 6. Prediction

* Generating final predictions on `test.csv` for Kaggle submission

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Jupyter Notebook

---

## 📌 Key Insights

* Synthetic datasets can closely mimic real-world distributions but still introduce subtle shifts that affect model generalization.
* Feature engineering plays a crucial role in improving regression performance.
* Ensemble methods typically outperform simple linear models in this task.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/road-accident-risk-prediction.git
cd road-accident-risk-prediction
```

2. Open the notebook:

```bash
jupyter notebook main_code.ipynb
```

3. Run all cells to reproduce the workflow and generate predictions.


---


