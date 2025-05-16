# Healthcare-Appointment-No-Show-Prediction

✅ Objective:
To predict whether a patient will miss a scheduled healthcare appointment and provide actionable insights to reduce no-show rates and optimize hospital scheduling.

🧰 Tools Used:
Python (Pandas, Scikit-learn, Matplotlib, SMOTE)

Power BI (Data visualization, dashboards)

📁 Dataset Overview:
57,000+ patient appointment records

Features included: age, gender, appointment day, SMS received, medical conditions, scholarship, and no-show status

🧹 Data Cleaning & Preprocessing (Python):
Removed unnecessary fields (PatientID, AppointmentID)

Converted No-show column to binary (Yes = 1, No = 0)

Created new features: day of the week, age groups

Handled imbalanced data using SMOTE

Encoded categorical features using get_dummies

🤖 Modeling: Decision Tree Classifier
Trained on SMOTE-balanced data

Target Variable: No-show (0 = showed up, 1 = missed)

Model used: DecisionTreeClassifier(max_depth=5)

Achieved good accuracy and precision on test data

Evaluated using: Accuracy Score, Confusion Matrix, Classification Report

✅ Key Features Impacting No-Shows:
SMS Reminders: Patients without SMS reminders had higher no-show rates

Age Groups: Younger patients were more likely to miss appointments

Weekday: No-shows were more frequent on Mondays and Fridays

📈 Power BI Dashboard Highlights:
Filters: Gender, Scholarship status, Age range, Chronic conditions

Charts:

No-show % by weekday and gender

Distribution of SMS reminders vs no-show

Age vs appointment attendance

Interactive slicers enabled dynamic filtering by demographics and conditions

💡 Optimization Recommendations:
Send SMS reminders to all patients, especially younger age groups

Schedule high-risk patients earlier in the week (e.g., avoid Fridays)

Prioritize outreach to patients with chronic illness or no prior follow-up

✅ Deliverables:
Python-based Prediction Model

Power BI Insight Dashboard

Summary report with scheduling recommendations
