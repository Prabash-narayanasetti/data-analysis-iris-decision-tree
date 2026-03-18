# Iris Species Classification Project

## Project Overview
This project demonstrates a full machine learning workflow using the classic Iris dataset. The goal is to accurately predict the species of a flower based on its sepal and petal measurements.

## Key Features
* **Exploratory Data Analysis (EDA):** Used Seaborn pairplots and correlation heatmaps to understand feature relationships.
* **Data Preprocessing:** Handled categorical targets using Label Encoding.
* **Model Building:** Implemented a Decision Tree Classifier using Scikit-Learn.
* **Optimization:** Performed model pruning (Hyperparameter Tuning) using `max_depth` and `entropy` to ensure model efficiency.
* **Evaluation:** Achieved high accuracy, validated by Confusion Matrices and Classification Reports.

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## Results
The model identified **Petal Width** and **Petal Length** as the most significant predictors. The final tuned model achieved an accuracy score of 1.0 (100%) on the test dataset.
