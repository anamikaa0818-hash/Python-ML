# Mutual Fund Customer Churn Prediction using Machine Learning

## Project Overview

This project focuses on predicting **customer churn in mutual fund investments** using machine learning classification techniques. Churn refers to customers who close or discontinue their mutual fund investments.

By analyzing customer demographics, investment behavior, and financial activity, machine learning models are trained to classify whether a customer is likely to churn or not.

The goal of this project is to help financial institutions **identify high-risk customers early and improve retention strategies**.

---

## Dataset

The dataset contains information related to mutual fund investors including:

* Customer demographic details
* Investment type
* Payment mode
* Number of mutual funds invested
* Investment tenure
* Investment amount
* Additional products purchased

The dataset is used to generate a **binary classification target variable called `Churn`**.

### Target Variable

* **Churn = 1** → Customer closed their mutual fund
* **Churn = 0** → Customer still active

---

## Data Preprocessing

Several preprocessing steps were performed before training the models:

1. Removal of irrelevant columns such as client IDs.
2. Handling missing values.
3. Feature engineering including:

   * Age calculation from Date of Birth
   * Tenure category creation (Short-term, Mid-term, Long-term)
   * Investment frequency
   * Diversification score
4. Encoding categorical variables using **One-Hot Encoding**.
5. Feature scaling using **StandardScaler**.
6. Handling class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**.

---

## Exploratory Data Analysis

Exploratory data analysis was performed to understand relationships between variables.

Visualizations include:

* Count plots of categorical variables
* Scatter plots for investment vs tenure
* Correlation heatmap of numerical features
* Distribution of churned vs non-churned customers

These visualizations help identify patterns in customer behavior.

---

## Machine Learning Models Used

Multiple classification algorithms were implemented and compared:

* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* Naive Bayes
* XGBoost
* LightGBM

Each model was trained using a **train-test split (80%-20%)** and evaluated using standard classification metrics.

---

## Model Evaluation Metrics

The following metrics were used to evaluate model performance:

* Accuracy
* Precision
* Recall
* Confusion Matrix
* Classification Report
* K-Fold Cross Validation

Learning curves were also generated to analyze model training behavior.

---

## Results

Different models were compared based on accuracy and other evaluation metrics.

Visualization plots were created to compare:

* Accuracy scores
* Precision scores
* Recall scores

These comparisons help identify the most suitable model for predicting churn.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* Matplotlib
* Seaborn
* Imbalanced-learn (SMOTE)

---

## Project Structure

```
project-folder
│
├── mf_data.csv
├── final_project.ipynb
├── README.md
└── visualizations
```

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/mutual-fund-churn-prediction.git
```

2. Install required libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm imbalanced-learn
```

3. Run the Jupyter Notebook

```bash
jupyter notebook final_project.ipynb
```

---

## Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Deployment using a web application
* Real-time churn prediction system

---

## Author

Anamika
MSc Computer Science and Data Analytics
Digital University Kerala

---
