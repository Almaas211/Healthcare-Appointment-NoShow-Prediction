# Healthcare Appointment No-Show Prediction

## 📌 Project Overview
This project focuses on predicting whether patients will miss their scheduled healthcare appointments (no-shows) using machine learning techniques and analyzing key influencing factors through an interactive Power BI dashboard.

Missed appointments cause inefficiency, increased waiting times, and revenue loss in healthcare systems. This project helps hospitals optimize scheduling and reduce no-show rates.

---

## 🎯 Objectives
- Predict whether a patient will miss an appointment
- Analyze the impact of SMS reminders, age, weekday, and waiting time
- Build a machine learning prediction model
- Create an interactive Power BI dashboard for insights
- Provide optimization recommendations for healthcare scheduling

---

## 🛠 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
  - Scikit-learn
  - Imbalanced-learn (SMOTE)
  - XGBoost
- **Power BI**
- **Google Colab / Jupyter Notebook**

---

## 📊 Dataset Description
- ~110,000 healthcare appointment records
- Each record represents one patient appointment

### Key Features:
- Gender, Age
- Medical conditions (Diabetes, Hypertension, Alcoholism)
- SMS_received
- ScheduledDay, AppointmentDay
- WaitingDays
- Target variable (No-show)

---

## 🧹 Data Cleaning & Feature Engineering
- Removed unnecessary ID columns
- Converted date columns to datetime format
- Created new features:
  - WaitingDays
  - WaitingBin
  - AgeGroup
  - Appointment Weekday
- Encoded categorical variables
- Created binary target variable for prediction

Cleaned dataset file:
- `cleaned_no_show_data_v2.csv`

---

## 🤖 Machine Learning Models
The following models were trained and evaluated:
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### Techniques Used:
- Train-test split
- SMOTE for class imbalance handling
- Evaluation metrics:
  - Accuracy
  - ROC-AUC
  - Precision, Recall, F1-score

Random Forest and XGBoost showed better performance in identifying appointment no-shows.

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was created with the following insights:
- Overall No-show Rate
- No-show Rate by SMS Received
- No-show Rate by Age Group
- No-show Rate by Appointment Weekday
- No-show Rate by Waiting Days

Dashboard file:
- `Healthcare_NoShow_PowerBI_Dashboard.pbix`

---

## 🧠 Key Insights
- Patients who did not receive SMS reminders have higher no-show rates
- Teenagers and young adults are more likely to miss appointments
- Weekend appointments show higher no-show trends
- Longer waiting times significantly increase no-show probability

---

## 📌 Optimization Recommendations
- Send SMS reminders for all appointments
- Reduce long waiting periods
- Provide flexible scheduling for high-risk age groups
- Optimize weekend appointment slots

---

## 📁 Project Files
- `cleaned_no_show_data_v2.csv`
- `Healthcare_NoShow_PowerBI_Dashboard.pbix`
- Jupyter Notebook / Colab file for model training

---

## ✅ Conclusion
This project demonstrates how machine learning and data visualization can be effectively used to predict healthcare appointment no-shows and improve scheduling efficiency.

---

### 👩‍💻 Author
**Almaas Labbai**
