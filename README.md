# Credit Risk Prediction System
### Customer Credit Risk Prediction Using Machine Learning

## 1. Project Overview

This project aims to develop a machine learning system to predict customer credit risk and estimate the probability of loan default based on financial and loan-related features.

The system applies various machine learning algorithms to analyze customer data, identify potential default risks, and improve credit risk assessment.

## 2. Project Objectives

- Explore and analyze customer credit data.
- Build a data preprocessing and cleaning pipeline.
- Apply feature engineering techniques to improve data quality.
- Develop and compare multiple classification models.
- Optimize decision thresholds to improve default detection.
- Select the best-performing model for credit risk prediction.

## 3. Project Workflow

### Step 1: Data Understanding & Exploratory Data Analysis (EDA)
- Explore dataset structure and feature distributions.
- Analyze relationships between different features.
- Visualize data patterns and identify factors related to credit risk.

### Step 2: Data Preprocessing
- Handle missing and duplicate values.
- Detect and handle outliers.
- Encode categorical variables.
- Scale numerical features.

### Step 3: Feature Engineering
- Select relevant features.
- Transform numerical and categorical data.
- Prepare datasets for model training.

### Step 4: Model Development

Train and compare the following machine learning models:
- Logistic Regression
- XGBoost
- LightGBM

### Step 5: Model Evaluation & Optimization
- Evaluate models using ROC-AUC, Precision, Recall, and F2-score.
- Optimize decision thresholds.
- Address class imbalance to improve default prediction performance.

## 4. Model Performance

The optimized XGBoost model achieved the following results:

| Evaluation Metric | Score |
|---|---:|
| ROC-AUC | **0.9477** |
| F2-score | **0.8050** |

These results demonstrate the model's ability to distinguish between customers with different levels of credit default risk.

## 5. Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas, NumPy | Data processing and analysis |
| Matplotlib, Seaborn | Data visualization |
| Scikit-learn | Data preprocessing and model evaluation |
| XGBoost | Machine learning model development |
| LightGBM | Machine learning model development |

## 6. Project Structure

```text
DS112_Credit_Risk_Prediction_System/
│
├── EDA/                  # Exploratory Data Analysis
├── Data Preprocessing/   # Data cleaning and preprocessing
├── Feature Engineering/  # Feature transformation and selection
├── Build Model/          # Model training and evaluation
├── dataset/              # Project datasets
└── README.md             # Project documentation
```

*Note: Update the folder structure to match the actual repository.*

## 7. Key Contributions

- Performed exploratory data analysis and data visualization.
- Developed data preprocessing and feature engineering pipelines.
- Trained and compared multiple classification models.
- Optimized decision thresholds for imbalanced classification.
- Evaluated model performance and selected the best-performing model.

## 8. Author

**Nguyen Gia Lam**

**Project Domain:** Machine Learning / Data Science / Financial Risk Analysis

**Course:** IE221

---
