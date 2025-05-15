# Healthcare-Appointment-No-Show-Prediction

🏥 Healthcare Appointment No-Show Prediction

📌 Overview

This project uses a dataset of medical appointments to predict whether a patient will show up for their scheduled appointment. A Decision Tree Classifier is used for modeling, along with exploratory data analysis and feature engineering to understand the factors influencing no-shows.


🎯 Objective

To build a predictive model that classifies whether a patient will attend their appointment based on features like age, gender, SMS received, and waiting time.

🛠 Tools & Technologies

Python

Pandas

Seaborn

Matplotlib

Scikit-learn


📊 Dataset Summary

Features: Gender, Age, SMS_received, Scholarship, Hypertension, Alcoholism, Diabetes, Handicap, etc.

Target: Showed_up (1 = Showed up, 0 = No-show)

New Feature: waiting_days (difference between appointment and scheduling dates)


🔍 Exploratory Data Analysis (EDA)

Target Distribution: Countplot of show vs no-show appointments.

Feature Engineering:

Converted ScheduledDay and AppointmentDay to datetime

Created a new column waiting_days

Categorical Encoding: Gender (F = 0, M = 1)


🧠 Model Building

Algorithm Used: Decision Tree Classifier

Train/Test Split: 80/20

Model Parameters: max_depth=5, random_state=0


✅ Evaluation Metrics:

Accuracy: Displayed via accuracy_score()

Confusion Matrix and Classification Report used for deeper insights


📁 Files Included

healthcare.csv – Raw dataset

cleaned_healthcare_data.csv – Cleaned version after preprocessing

Accuracy: 0.79
Confusion Matrix:
[[127  33]
 [ 29 150]]
Classification Report:
              precision    recall  f1-score   support
           0       0.81      0.79      0.80       160
           1       0.82      0.84      0.83       179


✅ Conclusion

This model provides a good foundation to understand what drives appointment no-shows in the healthcare industry. With further feature engineering and tuning, this can help in designing patient reminder systems and improving attendance rates.
