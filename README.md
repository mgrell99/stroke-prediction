# Stroke Prediction Project

This project aims to predict the likelihood of a stroke based on patient health data using various classification algorithms.

## Objective
To develop and evaluate machine learning models that classify whether a patient is at risk of experiencing a stroke, based on features such as age, hypertension, heart disease, smoking status, BMI, and more.

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas & NumPy (data handling)
- scikit-learn (classification models & evaluation)
- Matplotlib / Seaborn (data visualization)

## Models Used
- Decision Tree
- Naive Bayes
- Random Forest
- Dummy Classifier (baseline)

## Evaluation
- **Nested Cross Validation**
- **Metrics:** F1 Score, Recall

## Key Steps
1. Data cleaning and preprocessing  
2. Feature selection and engineering  
3. Model training and hyperparameter tuning  
4. Performance comparison using nested CV  
5. Interpretation of results

## Dataset
This project uses a publicly available stroke dataset (e.g. from Kaggle).

## Outcome
The Random Forest model showed the best performance in terms of recall, indicating a good ability to identify high-risk patients. Results were summarized and compared across different validation strategies.

---

