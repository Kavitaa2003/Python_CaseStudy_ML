# Advertising Case Study – Machine Learning

## Project Description
This project implements a Machine Learning model using Linear Regression to analyze the relationship between advertising budget and product sales.

The dataset contains advertising budgets spent on TV, Radio, and Newspaper channels. The goal of this project is to predict sales based on advertising spending using a regression model.

This project demonstrates the complete Machine Learning workflow including data preprocessing, model training, evaluation, and visualization.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Steps Implemented

### 1. Load Dataset
The dataset is loaded using Pandas from the file `Advertising.csv`.

### 2. Remove Unwanted Columns
If the dataset contains an unnecessary column such as `Unnamed: 0`, it is removed.

### 3. Check Missing Values
The program checks whether the dataset contains missing values.

### 4. Display Statistical Summary
Statistical information of the dataset is displayed using the `describe()` function.

### 5. Correlation Analysis
The correlation between advertising channels and sales is calculated.

### 6. Split Dataset
The dataset is divided into:

Independent Variables (X)
- TV
- Radio
- Newspaper

Dependent Variable (Y)
- Sales

### 7. Train-Test Split
The dataset is split into training and testing sets using train_test_split().

80% Training Data  
20% Testing Data

### 8. Train the Model
A Linear Regression model is created and trained using the training dataset.

### 9. Test the Model
The trained model predicts sales using the testing dataset.

### 10. Evaluate Model Performance
The model performance is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 11. Model Coefficients
The coefficients of each advertising channel are displayed to understand their impact on sales.

### 12. Actual vs Predicted Comparison
The program compares actual sales values with predicted sales values.

### 13. Visualization
A scatter plot is created to visualize the relationship between Actual Sales and Predicted Sales.

---

## Dataset Information

| Column | Description |
|------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspaper |
| Sales | Sales generated |

---

## Project Structure

Advertising_Casestudy
│
├── Advertising.csv
├── advertising_analysis.py
└── README.md

---

## How to Run the Project

### Clone the repository

git clone https://github.com/Kavitaa2003/Python_CaseStudy_ML.git

### Install required libraries

pip install pandas numpy matplotlib scikit-learn

### Run the project

python advertising_analysis.py

---

## Output
The program will:
- Display dataset information
- Train a regression model
- Predict sales
- Show model evaluation metrics
- Plot Actual Sales vs Predicted Sales

---

## Author
Kavita Shewale  
Machine Learning Case Study Project
