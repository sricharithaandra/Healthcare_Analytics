Healthcare Analytics Capstone:

Predictive Modeling, Patient Clustering & Marketing Strategy | Python · Excel · Tableau

Overview:

This project applies machine learning techniques to analyze 55,500 synthetic patient records to predict key patient outcomes and identify meaningful patient segments for targeted healthcare marketing strategies.

Dataset: 

Synthetic healthcare dataset is sourced from Kaggle as it mimics real-world patient records without compromising patient confidentiality.
Key Variables: Age, Gender, Blood Type, Medical Condition, Insurance Provider, Billing Amount, Admission Type, Medication, Test Results, Length of Stay

Research Questions:
- Q1. Can we predict a patient's test result based on demographic and medical information?
- Q2. Can a patient's length of stay be estimated based on available variables?
- Q3. How can patients be grouped into distinct segments, and how do these segments differ?

Tools & Technologies:
- Python (pandas, scikit-learn, matplotlib): Data preprocessing, predictive modeling, clustering
- Excel: Data cleaning, exploratory analysis
- Tableau: Visual reporting

Key Findings:
- Random Forest was the best performing model for both classification (accuracy: 0.417) and regression (R²: 0.045).
- Model performance was limited by the synthetic nature of the dataset as the available variables were not strong enough predictors of test results or length of stay.

Recommendations: 
- Data improvement: Include medication frequency, family health history, and complete medical records beyond admission data to improve model performance.
- Hospital resource management: Allocate resources based on admission type patterns; prioritize training for urgent and emergency admissions.

Limitations:
- HIPAA constraints make real patient data difficult to obtain. 

Author:

Sricharitha Andra 

M.S. Marketing Analytics & Insights - Wright State University, 2025
