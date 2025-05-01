# Student-Dropout-Predictor

This project uses a supervised machine learning model to predict student dropout risk based on academic and demographic attributes. The goal is to identify at-risk students and enable timely interventions using explainable, interpretable models.

## Dataset

- Source: UCI Machine Learning Repository  
  https://archive.ics.uci.edu/ml/datasets/Student+Performance

- Backup copy included: `data.csv`

- Features include:
  - Age, Gender
  - Grade level, Previous grades, Parental education
  - Attendance, Number of failures
  - Internet access, Study time, Health, and more

- Target variable:
  - `Dropout` (Binary classification: 1 = Dropped out, 0 = Continued)

## Model

- Models compared:
  - Logistic Regression
  - Random Forest
  - XGBoost

- Final Model: XGBoost (after hyperparameter tuning)

- Data Preprocessing:
  - One-hot encoding for categorical variables
  - Standard scaling for numerical features
  - Train-test split (70:30)

## Evaluation Metrics

- Accuracy: 91%
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## Key Learnings

- Model comparison and selection for binary classification
- Logistic regression interpretability in high-stakes predictions
- Importance of preprocessing and feature selection
- Early detection of student dropout risks using academic data

## Files in this Repository

- `Student_Dropout_Prediction.ipynb` — Jupyter notebook with all code
- `data.csv` — Local copy of UCI student dataset

## Author

Aditya Arte  
MBA + Business Analytics Dual Degree Candidate  
Hult International Business School  
[LinkedIn Profile](https://www.linkedin.com/in/aditya-arte/)
