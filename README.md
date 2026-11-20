# Student Grade Prediction

## Project Overview
This project uses Machine Learning regression techniques to predict students' final Mathematics grades based on historical academic and personal information.

## Dataset
The project uses the Student Performance dataset from the UCI Machine Learning Repository.

Two CSV files are included:
- `student-mat.csv`: Mathematics course data.
- `student-por.csv`: Portuguese course data.

The main prediction task uses the Mathematics dataset, which contains 395 students and 33 attributes.

The initial analysis also examines the matching between students in both datasets.

## Project Workflow
1. Data Loading and Understanding
2. Data Quality Checking
3. Exploratory Data Analysis (EDA)
4. Numerical and Categorical Feature Analysis
5. Train/Test Split
6. Data Preprocessing
7. Regression Model Training
8. Model Evaluation
9. Cross-Validation
10. Hyperparameter Tuning
11. Academic Support Identification

## Machine Learning Models
- Linear Regression
- Ridge Regression
- Decision Tree Regressor

## Model Evaluation Results

| Model | R² | RMSE | MAE |
|---|---:|---:|---:|
| Linear Regression | 0.724 | 2.378 | 1.647 |
| Ridge Regression | 0.736 | 2.328 | 1.589 |
| Decision Tree | 0.731 | 2.347 | 1.380 |

Ridge Regression achieved the best overall performance based on R² and RMSE.

## Academic Support Identification

Students with predicted final grades of 10 or below are flagged for additional academic review.

Test-set results:
- Precision: 94.74%
- Recall: 94.74%
- F1 Score: 94.74%
- Accuracy: 94.94%

These predictions are intended to support teachers in identifying students who may need additional attention.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset Source
UCI Machine Learning Repository:

https://doi.org/10.24432/C5TG7T

Original dataset authors: Paulo Cortez and Alice Silva.
