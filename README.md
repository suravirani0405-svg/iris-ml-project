# Iris Flower Classification 🌸

A machine learning classification project that predicts the species of an Iris flower using its sepal and petal measurements.

## Project Overview

The project uses the Iris dataset to classify flowers into three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Features

The model uses four input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Machine Learning Models

Three classification algorithms were trained and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest

## Model Evaluation

5-fold cross-validation was used to compare the models.

| Model | Cross-Validation Accuracy |
|---|---:|
| Logistic Regression | 97.33% |
| Decision Tree | 96.66% |
| Random Forest | 96.00% |

Logistic Regression achieved the best cross-validation performance.

## Prediction

The trained Logistic Regression model was used to predict a new flower:

```text
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2