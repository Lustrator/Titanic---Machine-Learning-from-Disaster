# Titanic - Machine Learning from Disaster

## Overview

This project is my practical introduction to machine learning and feature engineering using the Titanic dataset from Kaggle.

The goal was simple:
predict whether a passenger survived the disaster based on available passenger information.

Instead of only training a model, I focused on understanding:
- preprocessing,
- feature engineering,
- validation,
- data leakage,
- and how models actually work with structured data.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## Data Preparation

During preprocessing I worked with:
- missing values,
- categorical encoding,
- feature extraction,
- and dataset alignment.

### Features used:
- Passenger class
- Sex
- Age
- Fare
- Family size
- Is alone
- Embarked
- Passenger title extracted from names

Examples:
- `Family Size`
- `Is Alone`
- `Title_Mr`, `Title_Miss`, etc.

---

## Model

Model used:
- Random Forest Classifier

Main parameters:
- `n_estimators=1000`
- `max_depth=4`
- `random_state=42`

---

## Result

Public Kaggle score:
0.78708

The project helped me better understand:
- feature engineering,
- train/test separation,
- validation mistakes,
- and how small preprocessing decisions affect model quality.

---

## What I Learned

One of the most important lessons was understanding how easy it is to accidentally create data leakage or invalidate evaluation.

This project was less about chasing leaderboard scores and more about learning how machine learning pipelines actually behave in practice.

Kaggle: https://www.kaggle.com/code/iriyablood/titanic-machine-learning-from-disaster/notebook
