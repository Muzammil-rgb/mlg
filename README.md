# Loan Approval Prediction System

A machine learning web application that predicts whether a loan application is likely to be **approved** or **rejected** based on applicant and financial details.

---

## Project Overview

The **Loan Approval Prediction System** is a machine learning project developed to automate the prediction of loan approval status using applicant information such as income, loan amount, CIBIL score, loan term, employment status, education, asset value, and other related features.

The main goal of this project is to build an end-to-end **classification system** that can assist in loan approval decision-making by analyzing historical data and identifying patterns. The project covers the complete machine learning workflow, including:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature encoding
* Model training
* Model evaluation
* Model saving
* Web deployment using Streamlit

---

## Features

* Predicts whether a loan will be **Approved** or **Rejected**
* Uses applicant financial and personal details as input
* Performs data cleaning and preprocessing
* Applies machine learning classification algorithms
* Compares **Logistic Regression** and **Random Forest Classifier**
* Saves the trained model using **Joblib**
* Provides a **Streamlit web application** for easy user interaction

---

## Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Streamlit**
* **Joblib**

---

## Machine Learning Workflow

This project follows a complete machine learning pipeline:

### 1. Data Preprocessing

The dataset is cleaned and prepared before training. This includes:

* Checking missing values
* Standardizing column names
* Handling categorical variables
* Selecting relevant input features

### 2. Exploratory Data Analysis (EDA)

EDA is performed to understand the dataset and identify relationships between variables. Visualizations such as count plots, histograms, and heatmaps are used.

### 3. Feature Encoding

Categorical variables such as education, employment status, self-employed status, and property type are converted into numerical format for model training.

### 4. Train-Test Split

The dataset is divided into:

* **Training data** for model learning
* **Testing data** for performance evaluation

### 5. Model Training

Two machine learning models are trained and compared:

* **Logistic Regression**
* **Random Forest Classifier**

### 6. Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification report

### 7. Model Saving

The best-performing model is saved using **Joblib** and later loaded into the Streamlit application.

### 8. Deployment

The final model is deployed as a **Streamlit web app**, allowing users to enter applicant details and get instant predictions.

---

## Input Features Used

The model uses the following input features:

* **CIBIL Score**
* **Annual Income**
* **Loan Amount**
* **Loan Term**
* **Asset Value**
* **Education**
* **Employment Status**
* **Self-Employed Status**
* **Property Type**
* **Number of Dependents**

---

## Output

The application predicts one of the following outcomes:

* **Loan Approved**
* **Loan Rejected**

---

## Model Performance

After comparing multiple models, the **Random Forest Classifier** performed better and was selected as the final model.

* **Best Model:** Random Forest Classifier
* **Accuracy:** Approximately **79.86%**

---

## Project Structure

```bash
loan-approval-prediction/
│
├── app.py
├── loan_approval_model.pkl
├── requirements.txt
├── README.md
├── loan_approval_prediction.ipynb
└── screenshots/
    └── app_screenshot.png
```

### File Description

* **app.py** → Streamlit web application file
* **loan_approval_model.pkl** → Saved trained machine learning model
* **requirements.txt** → Required Python libraries
* **README.md** → Project documentation
* **loan_approval_prediction.ipynb** → Jupyter notebook containing EDA, preprocessing, training, and evaluation
* **screenshots/** → Application screenshots







## Example Workflow

1. Enter applicant details such as income, loan amount, CIBIL score, employment status, and property type.
2. Click the prediction button.
3. The model processes the input and predicts whether the loan is likely to be approved or rejected.
4. The result is displayed on the screen.

---


---

## What I Learned

Through this project, I learned how to build a complete machine learning classification system from start to finish. This project helped me gain practical experience in:

* Data preprocessing and cleaning
* Exploratory data analysis
* Encoding categorical features
* Training classification models
* Comparing model performance
* Saving trained models
* Building and deploying a Streamlit web application

---

## Future Improvements

The project can be improved further by:

* Performing **hyperparameter tuning** to improve accuracy
* Adding more input features
* Testing additional machine learning models
* Deploying the app online
* Improving the user interface
* Adding explainable AI features such as feature importance

---

## Conclusion

The **Loan Approval Prediction System** demonstrates how machine learning can be used to solve a real-world financial problem. By analyzing applicant and financial details, the system predicts whether a loan is likely to be approved or rejected. This project covers the full machine learning lifecycle and provides a practical example of how predictive models can be integrated into a web application.

---


