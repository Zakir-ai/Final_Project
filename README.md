# 🏥 Healthcare Appointment No-Show Prediction

This project uses machine learning and Power BI to predict whether a patient will miss a scheduled medical appointment and provides strategic recommendations to reduce no-show rates.

---

## 📚 Project Objective

- Predict no-show probability using historical appointment data  
- Analyze trends (e.g., SMS, age, weekday) affecting patient attendance  
- Build an interactive dashboard and generate scheduling recommendations  

---

## 🧰 Tools & Technologies

- **[Python](https://www.python.org/downloads/)** – Core programming language
- **[Pandas](https://pandas.pydata.org/)** – Data preprocessing and manipulation
- **[Scikit-learn](https://scikit-learn.org/stable/)** – ML models and evaluation
- **[XGBoost](https://xgboost.readthedocs.io/)** – Gradient boosting classifier
- **[Seaborn](https://seaborn.pydata.org/)** – Visual exploration and trends
- **[Power BI](https://powerbi.microsoft.com/desktop/)** – Interactive dashboards
- **[Google Colab](https://colab.research.google.com/)** – Notebook execution
- **[Microsoft Word](https://www.microsoft.com/en-us/microsoft-365/word)** / PDF – Final reporting

---

## 📋 Steps Followed

1. **Data Cleaning** – Handled date parsing, removed invalid ages, encoded categories  
2. **EDA** – Analyzed trends like SMS reminders, weekdays, and waiting time  
3. **Feature Engineering** – Added new columns like `waiting_days`, `appointment_day_of_week`  
4. **Modeling** – Trained Decision Tree, Random Forest, and XGBoost models  
5. **Evaluation** – Compared models using Accuracy and F1 Score  
6. **Visualization** – Designed a Power BI dashboard to show insights  

---

## 🔍 Model Performance

| Model              | Accuracy | F1 Score |
|-------------------|----------|----------|
| Decision Tree      | 60.53%   | ~0.61    |
| XGBoost            | 83.48%   | ~0.83    |
| Random Forest      | 84.68%   | ~0.85    |

---

## 📊 Dashboard Highlights

- No-show rates by day of week, age, gender  
- Effects of SMS reminders  
- Relationship with waiting days and chronic conditions  

---

## ✅ Recommendations

- Send SMS reminders 24–48 hours in advance  
- Avoid scheduling high-risk patients on Mondays  
- Follow up with patients who previously missed appointments  
- Schedule elderly patients for later time slots  
- Consider teleconsultation options for remote patients  

---

## 📄 Project Files

- `Medical_Appointment.ipynb` – Model development notebook  
- `Medical.pbix` – Interactive Power BI dashboard  
- `Medical_Appointment_Report.pdf` – Full project report  
- `Recommendations.pdf` – Strategic suggestions  

---
