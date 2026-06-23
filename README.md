# Hospital-Readmission-Prediction-Using-Logistic-Regression-and-Random-Forest
Impact of Medication and Clinical Factors on Hospital Readmission Prediction Using Machine Learning: A Comparative Study of Logistic Regression and Random Forest


Hospital readmission is a major challenge in healthcare systems, leading to increased medical costs, resource utilization, and patient burden. Early identification of patients at risk of readmission enables healthcare providers to implement preventive measures and improve patient outcomes.

This project aims to predict whether a patient is likely to be readmitted to the hospital using demographic information, diagnosis history, hospitalization records, medication details, and previous healthcare utilization data. The dataset consists of 66,587 training records and 16,647 testing records with 48 features describing various clinical and patient-related factors.

A comprehensive machine learning pipeline was developed that included data cleaning, missing value treatment, duplicate removal, feature engineering, categorical variable encoding, and exploratory data analysis. Visualizations were used to identify patterns between patient characteristics and readmission outcomes.

Two classification models were developed and compared: Logistic Regression and Random Forest. Hyperparameter tuning was performed using GridSearchCV to optimize model performance. The models were evaluated using Accuracy, Precision, Recall, and F1 Score, with F1 Score serving as the primary evaluation metric due to the class imbalance present in the dataset.

The final model successfully identifies patients at higher risk of hospital readmission by analyzing factors such as length of hospital stay, number of medications, previous inpatient visits, emergency visits, and diagnosis history. Feature importance analysis was conducted to understand the key drivers influencing readmission predictions.

The developed solution demonstrates how machine learning can support healthcare decision-making by enabling early risk detection, improving patient monitoring strategies, reducing avoidable readmissions, and optimizing healthcare resource allocation. The project provides a scalable foundation for implementing predictive analytics in real-world healthcare environments.
