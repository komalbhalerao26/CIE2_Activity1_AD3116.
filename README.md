# CIE 2 – Activity 1: Multiple Linear Regression

## Student Information
- **Name:** Komal Bhalerao
- **Roll Number:** AD3116
- **College:** Zeal College of Engineering & Research, Narhe, Pune
- **Department:** Artificial Intelligence & Data Science
- **Course:** Regression and Classification Algorithms
- **Academic Year:** 2026–27

## 1. Project Title
Multiple Linear Regression for Predicting Diabetes Disease Progression.

## 2. Objective
To understand and implement Multiple Linear Regression using Python. The activity studies how multiple numerical input features influence a continuous target variable and evaluates the model using different regression metrics.

## 3. Dataset Description
- **Dataset Name:** Diabetes Dataset
- **Dataset Source:** Scikit-learn Built-in Dataset
- **Source Link:** https://scikit-learn.org/stable/datasets/toy_dataset.html
- **Target Variable:** Disease Progression Score
- **Selected Input Features:**
  - BMI (Body Mass Index)
  - BP (Blood Pressure)
  - S5 (Blood Serum Measurement)

The dataset contains numerical medical measurements used for educational regression analysis.

## 4. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## 5. Implementation Steps
1. Imported the required Python libraries.
2. Loaded and explored the Diabetes dataset.
3. Checked missing values and duplicate records.
4. Selected BMI, BP and S5 as input features.
5. Created scatter plots and a correlation heatmap.
6. Performed manual Multiple Linear Regression calculations using the normal equation.
7. Verified manual calculations using Scikit-learn.
8. Divided the dataset into training and testing sets (80:20).
9. Built Single Linear Regression and Multiple Linear Regression models.
10. Generated predictions and compared actual and predicted values.
11. Evaluated the models using MAE, MSE, RMSE, R² and Adjusted R².
12. Performed residual analysis and checked multicollinearity using VIF.
13. Generated a prediction for a new example.

## 6. Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Adjusted R-squared

## 7. Results
The models were evaluated using the testing dataset. Single-feature and multiple-feature regression results were compared to understand whether using additional features improves prediction performance.

Actual and predicted values, regression metrics and diagnostic plots are available in the Jupyter Notebook.

## 8. Conclusion
Multiple Linear Regression helps understand the relationship between multiple input variables and a continuous target variable. The activity provided practical knowledge of data preprocessing, manual calculations, model training, prediction and evaluation.

The model is intended for educational purposes and should not be used as a medical diagnostic tool.

## 9. Repository Contents
- `CIE2_Activity1_Multiple_Linear_Regression_AD3116.ipynb` – Python implementation and outputs.
- `README.md` – Project description and implementation details.

## 10. Reference
Faculty GitHub Reference: https://github.com/complexiota
