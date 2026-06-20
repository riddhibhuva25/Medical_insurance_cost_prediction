#  Medical Insurance Cost Prediction using Machine Learning

##  Project Overview

This project focuses on predicting **medical insurance charges** based on an individual's demographic and health-related information using Machine Learning.

The goal is to build a regression model that can estimate insurance costs accurately and help understand the factors influencing medical expenses.

The project includes:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Data Preprocessing
* Model Selection
* Cross Validation
* Hyperparameter Tuning
* Model Evaluation
* Cost Prediction

---

##  Objective

The main objectives of this project are:

* Predict medical insurance charges
* Analyze factors affecting insurance costs
* Compare multiple regression algorithms
* Improve model performance using hyperparameter tuning
* Evaluate models using appropriate regression metrics

---

##  Machine Learning Concepts Used

* Supervised Learning
* Regression
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* Cross Validation
* Hyperparameter Tuning
* Pipeline
* ColumnTransformer
* Target Transformation

---

##  Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

##  Dataset Information

The dataset contains medical insurance records with the following features:

| Feature  | Description                              |
| -------- | ---------------------------------------- |
| age      | Age of the individual                    |
| sex      | Gender                                   |
| bmi      | Body Mass Index                          |
| children | Number of dependents                     |
| smoker   | Smoking status                           |
| region   | Residential region                       |
| charges  | Medical insurance cost (Target Variable) |

---

##  Exploratory Data Analysis (EDA)

Performed EDA to understand data distribution and relationships:

* Dataset structure and summary statistics
* Missing value analysis
* Correlation analysis
* Distribution plots
* Outlier detection
* Feature relationship analysis
* Insurance charge distribution

### Key Insights

* No missing values found
* Insurance charges are highly right-skewed
* Smoking status has a strong impact on insurance charges
* Age and BMI show moderate positive correlation with charges
* Presence of high-cost outliers in the target variable

---

##  Data Preprocessing

Preprocessing steps included:

* Train-Test Split
* One-Hot Encoding of categorical features
* Feature Scaling using StandardScaler
* ColumnTransformer implementation
* Pipeline creation to avoid data leakage

---

##  Models Implemented

The following regression models were evaluated:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

---

##  Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Cross-validation was used to compare model performance and select the best model.

---

##  Hyperparameter Tuning

Hyperparameter optimization was performed on top-performing models using:

* GridSearchCV

This helped improve prediction accuracy and generalization performance.

---

##  Project Workflow

```text
Data Collection
       ↓
Exploratory Data Analysis
       ↓
Data Preprocessing
       ↓
Feature Encoding & Scaling
       ↓
Baseline Model
       ↓
Cross Validation
       ↓
Model Selection
       ↓
Hyperparameter Tuning
       ↓
Final Evaluation
       ↓
Insurance Cost Prediction
```

---

##  Results

* Built multiple regression models for insurance cost prediction
* Identified smoking status as one of the most influential factors
* Applied pipelines to prevent data leakage
* Improved model performance through tuning and cross-validation
* Developed a complete end-to-end regression workflow

---

##  Real-World Applications

Medical insurance cost prediction can be useful for:

* Insurance premium estimation
* Healthcare analytics
* Risk assessment
* Policy pricing
* Cost forecasting
* Business decision-making

---

## ▶️ How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/riddhibhuva25/Medical_Insurance_Cost_Prediction.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook
```

---

##  Key Learnings

Through this project, I learned:

* Regression modeling techniques
* Feature engineering and preprocessing
* Model comparison using cross-validation
* Hyperparameter tuning with GridSearchCV
* Building reusable ML pipelines
* Evaluating regression models using MAE, RMSE, and R²

---

##  Author

**Riddhi Bhuva**

GitHub: https://github.com/riddhibhuva25/Medical_insurance_cost_prediction
