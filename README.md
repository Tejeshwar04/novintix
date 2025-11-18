# Healthcare Dataset Analysis and Machine Learning Pipeline

This project performs end-to-end data analysis and machine learning on the Healthcare Dataset sourced from Kaggle. It includes Exploratory Data Analysis (EDA), supervised learning for predicting medical test results, unsupervised anomaly detection for billing amounts, and an AI-driven doctor recommendation generator using LLMs.

## Dataset

Source: Kaggle Healthcare Dataset
Columns Included:

* Name
* Age
* Gender
* Blood Type
* Medical Condition
* Date of Admission
* Doctor
* Hospital
* Insurance Provider
* Billing Amount
* Room Number
* Admission Type
* Discharge Date
* Medication
* Test Results

---

## Task 1 — Exploratory Data Analysis (EDA)

### Objectives

1. Analyze numerical feature distributions:

   * Age
   * Billing Amount
   * Room Number

2. Visualize categorical feature frequencies:

   * Medical Condition
   * Admission Type
   * Medication

### Deliverables

* Histograms and boxplots for Age, Billing Amount, and Room Number
* Count plots for Medical Condition, Admission Type, and Medication
* Insights summarizing trends, skewness, and potential outliers

---

## Task 2 — Supervised Learning

The objective is to predict **Test Results** using available patient attributes.

### Steps

1. **Data Preprocessing**

   * Handle missing values
   * Encode categorical variables
   * Convert date fields to numerical features
   * Scale numerical features

2. **Train-Test Split**

   * Split the dataset into 80% training and 20% testing

3. **Model Training**

   * Build and train machine learning models (e.g., Random Forest, XGBoost, or CatBoost)
   * Tune hyperparameters for improved performance

4. **Evaluation**

   * Use metrics such as accuracy, precision, recall, and F1-score
   * Display predicted vs. actual values for test data

---

## Task 3 — Unsupervised Learning

### Anomaly Detection in Billing Amounts

Goal: Identify unusually high or low billing values that deviate from normal patterns.

### Methodology

* Use Isolation Forest or Local Outlier Factor
* Analyze distribution and compute anomaly scores
* Label entries as normal or anomalous
* Visualize detected anomalies

### Expected Findings

* Detection of rare cases with significantly high billing amounts
* Identification of unusually low billing instances possibly due to data entry issues or exceptional cases

---

## Task 4 — AI Task (LLM-Based Recommendation)

### AI Doctor Recommendation Generator

Input:

* Predicted Test Result
* Patient Age
* Medical Condition
* Medication

Process:

* Use a Large Language Model (LLM) to generate a concise, medically-oriented recommendation
* Provide supportive advice based on the predicted test outcome

### Example Output

A short, context-aware recommendation summarizing the patient’s condition and suggesting next steps for care and medication management.


## Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost / CatBoost
* Jupyter Notebook / Google Colab
* LLM-based text generation


If you need this rewritten in a shorter, longer, or more academic format, I can generate another version.
# novintix
