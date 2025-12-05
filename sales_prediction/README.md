#  Sales Prediction Using Machine Learning  
This project is part of the **CODSOFT Data Science Internship (Task 3)**.  
The goal is to predict product sales based on advertising spending using a regression model.

##  Project Overview  
Businesses use advertising on different platforms (TV, Radio, Newspaper) to increase sales.  
This project builds a **Linear Regression model** that predicts sales revenue based on:

- TV advertising budget  
- Radio advertising budget  
- Newspaper advertising budget  

It is a classic machine learning regression problem.

##  Dataset Used  
**File:** `advertising.csv`

Dataset Columns:

| Feature      | Description |
|--------------|-------------|
| TV           | Money spent on TV ads |
| Radio        | Money spent on Radio ads |
| Newspaper    | Money spent on Newspaper ads |
| Sales        | Total units sold (Target Variable) |

The dataset contains **200 rows** with numerical values only.  
No missing values.


##  Technologies & Libraries  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Jupyter Notebook  


##  Steps Performed  

### 1 Load and Explore Data  
- Viewed data structure  
- Checked missing values  
- Described statistical properties  

### 2 Data Visualization  
Created graphs to understand relationships:
- Pairplot (scatter relations between features)  
- Correlation heatmap (strong correlation with Sales)

### 3 Feature & Target Selection  
Features (X):  
`TV`, `Radio`, `Newspaper`  

Target (y):  
`Sales`

### 4 Train-Test Split  
Used 80% training and 20% testing data.

### 5 Model Training  
Trained a **Linear Regression** model using Scikit-Learn.

### 6 Model Evaluation  
Calculated:
- Mean Squared Error (MSE)  
- R² Score (Model Accuracy)

## Model Performance

Based on your execution:

- **MSE:** `2.9077`  
- **R² Score:** `0.9059`  

###  The model explains ~90.5% of the variance in sales.  
This is an **excellent** result for this dataset.


##  Sample Prediction  

### Input: [100, 25, 10]

### Output:
array([12.73])

### Interpretation:
If a company spends:  
- **100** on TV ads  
- **25** on Radio  
- **10** on Newspaper  

→ Predicted Sales ≈ **12.73 units**

---

## Files in This Folder  
- **sales.ipynb** — Complete Jupyter Notebook  
- **advertising.csv** — Dataset  
- **README.md** — Documentation  

---

##  Intern  
Renuka  
CODSOFT Data Science Internship – 2025

