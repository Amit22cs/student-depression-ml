# Student Depression Prediction using Machine Learning

This project applies machine learning to predict student depression based on academic, lifestyle, and mental health indicators. It aims to support early detection and intervention efforts to improve student well-being.

## 📁 Dataset Description

The dataset includes a variety of features:

- **Demographics**: Age, Gender, City, Degree
- **Academic & Work**: CGPA, Academic Pressure, Work Pressure, Study Satisfaction, Job Satisfaction
- **Lifestyle**: Sleep Duration, Dietary Habits, Work/Study Hours, Financial Stress
- **Mental Health**: Family History of Mental Illness, Suicidal Thoughts
- **Target**: Depression (Yes/No)

Data was cleaned and preprocessed to handle missing values, categorical encoding, and outliers.

## 🔍 Project Objectives

- Analyze factors that influence student depression
- Visualize relationships (e.g., sleep vs. CGPA, financial stress vs. depression)
- Build and evaluate a predictive machine learning model

## 📊 Methodology

1. Business Understanding  
2. Data Loading and Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Analytical Questions and Visualizations  
5. Model Building (Random Forest)  
6. Model Evaluation (Accuracy, Precision, Recall, Confusion Matrix)

## 🤖 Machine Learning Model

- **Model Used**: Random Forest Classifier
- **Target Variable**: Depression
- **Evaluation Metrics**:
  - Accuracy
  - Precision & Recall
  - Confusion Matrix

The model identifies students at high risk of depression with strong performance on recall and interpretability via feature importance.

## 📈 Key Insights

- High academic and work pressure negatively impact study/job satisfaction.
- Students with financial stress and less sleep show higher depression rates.
- A family history of mental illness significantly correlates with depression.
- Depression prevalence varies across degree programs and cities.

## 📌 How to Run

You can run the notebook using Google Colab:

1. Open the notebook `student_depression_prediction.ipynb`
2. Run each cell sequentially
3. All required libraries are commonly available in Colab (pandas, matplotlib, sklearn, etc.)

## 📄 Report

📑 A detailed PDF report is included here: [Project Report](./9139%20Amitkumar%20ML%20CA2.pdf)

## 🛡️ License

This project is licensed under the [MIT License](./LICENSE). You are free to use, modify, and distribute it with attribution.

## ✍️ Author

**Mehta Amitkumar Ravindra**  
TYCS-A, Roll No: 9139  
Pillai College of Arts, Commerce and Science  
Academic Year: 2024–25  
Project Guide: Sanjana Bhangale

