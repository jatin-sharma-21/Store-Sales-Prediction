# 🛒 Store Sales Prediction using Linear Regression

A Machine Learning project that predicts retail store sales using **Linear Regression**. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and statistical analysis to identify the factors influencing store sales.

---

## 📌 Project Overview

Accurate sales forecasting helps retailers optimize inventory, improve supply chain management, and make data-driven business decisions.

In this project, a **Linear Regression** model is developed to predict store sales based on product characteristics and outlet information. The project follows a complete machine learning workflow, from data cleaning to model evaluation.

---

## 🎯 Business Objective

Build a regression model capable of accurately predicting **Store Sales** using historical sales and product/store attributes.

---

## 📂 Dataset

The dataset contains information about products sold across different retail outlets.

### Key Features

- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type

### Target Variable

- **Item_Outlet_Sales**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## 📊 Exploratory Data Analysis (EDA)

The project performs comprehensive data analysis including:

- Data inspection
- Missing value analysis
- Duplicate value detection
- Descriptive statistics
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Correlation Heatmap
- Distribution Analysis
- Feature Relationships

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Missing value handling
- Duplicate record checking
- Outlier treatment using the IQR method
- Log transformation of the target variable
- One-Hot Encoding for categorical features
- Feature selection
- Train-Test Split (70:30)

---

## 🤖 Machine Learning Model

### Algorithm Used

- Linear Regression

### Model Workflow

1. Data Cleaning
2. Feature Engineering
3. One-Hot Encoding
4. Train-Test Split
5. Model Training
6. Sales Prediction
7. Performance Evaluation

---

## 📈 Model Evaluation

The model performance is evaluated using:

- R² Score
- Adjusted R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

The project also compares **training** and **testing** performance to evaluate model generalization.

---

## 📊 Statistical Analysis

To better understand feature significance, the project uses **Ordinary Least Squares (OLS)** Regression with **Statsmodels**, providing:

- Coefficient estimates
- P-values
- Confidence Intervals
- Statistical significance of predictors
- Overall model summary

---

## 📁 Project Structure

```
Store-Sales-Prediction/
│
├── store_sales_prediction.py
├── DS3_C6_S1_Regression_StoreSales_Data_Project.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Store-Sales-Prediction.git
```

Navigate to the project folder:

```bash
cd Store-Sales-Prediction
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

Run the project:

```bash
python store_sales_prediction.py
```

---

## 📌 Project Highlights

- Performed end-to-end data preprocessing and cleaning.
- Conducted extensive exploratory data analysis to identify sales trends.
- Applied feature engineering and one-hot encoding for categorical variables.
- Built a Linear Regression model for sales prediction.
- Evaluated model performance using multiple regression metrics.
- Used OLS Regression to analyze statistical significance of features.

---

## 🚀 Future Improvements

- Implement Ridge and Lasso Regression
- Hyperparameter Optimization
- Feature Selection using Recursive Feature Elimination (RFE)
- Compare with Decision Tree, Random Forest, XGBoost, and Gradient Boosting Regressors
- Deploy the model using Streamlit or Flask
- Build an interactive sales prediction dashboard


## 📜 License

This project is intended for educational and learning purposes.
