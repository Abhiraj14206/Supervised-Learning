Risk Alert Classifier

## Project Overview

This project develops a Machine Learning classification model to predict whether a customer belongs to a **High Risk** or **Low Risk** category. The notebook covers the complete machine learning workflow, including data preprocessing, model building, handling class imbalance, hyperparameter tuning, and model evaluation.

---

## Objective

The objective of this project is to:

- Understand the dataset
- Preprocess the data
- Build baseline classification models
- Handle imbalanced data using SMOTE
- Compare different machine learning algorithms
- Optimize model performance using GridSearchCV
- Evaluate the final model using various performance metrics

---

## Project Structure

```
Risk-Alert-Classifier/
│
├── Exam 3 (SL).ipynb                # Complete notebook
├── README.md                        # Project documentation
├── Risk_Alert_Classifier_Dataset.csv # Dataset
└── requirements.txt                 # Required libraries
```

---

## Workflow

### Part A – Conceptual Understanding

- Logistic Regression
- Precision vs Recall
- SMOTE
- Precision, Recall, F1 Score
- ROC Curve

---

### Part B – Dataset Preparation

- Load dataset
- Check missing values
- Explore dataset information
- Analyze target distribution
- Encode categorical variables using LabelEncoder
- Split dataset into training and testing sets

---

### Part C – Baseline Model

Implemented:

- Logistic Regression

Evaluation Metric:

- Accuracy Score

---

### Part D – Handling Imbalanced Data

Applied:

- SMOTE (Synthetic Minority Over-sampling Technique)

Compared:

- Precision
- Recall
- F1 Score

---

### Part E – Tree-Based Models

Implemented:

- Decision Tree Classifier
- Random Forest Classifier

Compared model accuracies.

---

### Part F – Hyperparameter Tuning

Optimized Random Forest using:

- GridSearchCV

Parameters Tuned:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split

---

### Part G – Model Evaluation

Performance metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

---

### Part H – Final Analysis

The notebook concludes with:

- Model comparison
- Performance analysis
- Final observations
- Best performing model selection

---

## Machine Learning Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Libraries Used

```python
pandas
numpy
matplotlib
scikit-learn
imbalanced-learn
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Risk-Alert-Classifier.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Dataset

The dataset contains customer information along with the target variable:

**Target Column**

```
risk_status
```

The target is used for binary classification.

---

## Evaluation Metrics

The project evaluates models using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

---

## Results

The notebook compares multiple machine learning models and identifies the best-performing model after hyperparameter tuning.

---

## Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Feature Engineering
- Cross Validation
- Model Deployment using Flask/FastAPI
- Explainable AI (SHAP/LIME)

---

## Author

Abhiraj Medhat

Machine Learning | Data Science | Artificial Intelligence

---
