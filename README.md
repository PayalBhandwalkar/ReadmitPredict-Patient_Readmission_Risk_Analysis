# 🏥 Patient Readmission Risk Analysis

A machine learning project to predict hospital patient readmission risk using structured healthcare data. This analysis aims to help hospitals allocate resources efficiently and reduce preventable readmissions by identifying high-risk patients.

---

## 📌 Project Objective

To build a predictive model that identifies patients at risk of readmission within 30 days after discharge. The project also explores key factors contributing to readmission, helping hospital administrators and clinicians make informed decisions.

---

## 📁 Dataset Description

- **Source**: Simulated patient data based on common hospital discharge records
- **Files Used**:
  - `patients.csv` — demographic and ID data
  - `admissions.csv` — admission dates, types, and diagnoses
  - `discharges.csv` — discharge dates, outcomes, and follow-up details

---

## 🧠 Key Features Used

- Patient demographics (age, gender)
- Admission and discharge type
- Primary and secondary diagnoses
- Number of prior admissions
- Length of stay
- Time since last discharge
- Insurance and payment type
- Comorbidities (e.g., diabetes, hypertension)

---

## 🔧 Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **IDE**: Jupyter Notebook
- **Visualization**: Tableau (for dashboard insights)

---

## 📊 Tableau Dashboard Insights

An interactive Tableau dashboard was created to help healthcare providers:
- Identify top factors affecting readmission
- Monitor readmissions by diagnosis group
- Visualize demographic and clinical risk distributions
- Anticipate bed demand based on urgency and readmission cycles

> [🔗 Link to Tableau Public Dashboard](#) *(Add your actual link)*

---

## 🚀 Project Workflow

1. **Data Cleaning & Merging**  
   - Handled missing values and merged datasets using patient IDs

2. **Exploratory Data Analysis (EDA)**  
   - Visualized trends in diagnosis, age, and readmission

3. **Feature Engineering**  
   - Created new variables like time_since_last_admission and comorbidity_score

4. **Model Building**  
   - Used Logistic Regression, Random Forest, and XGBoost
   - Evaluated models using accuracy, precision, recall, F1-score, ROC-AUC

5. **Interpretation & Deployment**  
   - Interpreted SHAP values and feature importance
   - Dashboard created in Tableau for clinical decision-making

---

## 📈 Results

- Best model: **XGBoost** with an AUC score of **0.84**
- Top predictors: **Number of prior admissions**, **length of stay**, **discharge type**, and **primary diagnosis**
- Helped simulate how timely interventions can reduce readmission by 12–15%

---

## ✅ Future Improvements

- Incorporate unstructured clinical notes using NLP
- Deploy as a real-time hospital triage tool
- Integrate with EHR systems via API

---

## 🤝 Acknowledgements

## 🤝 Acknowledgements

This project was inspired by the **Singapore General Hospital Bed Management System** case study from Harvard Business School, which highlighted the critical importance of proactive patient flow and resource planning in healthcare systems.

You can read my case study blog here: [📖 [Singapore Health System Case Study Blog](https://medium.com/@bhandwalkar.payal2001/beyond-the-bed-count-a-data-driven-approach-to-hospital-bed-management-at-singapore-general-0758123f49cf)](#) 

Thanks also to healthcare data simulation resources and open-source medical ML literature that helped shape this project.


---

## 📬 Contact

**Payal Bhandwalkar**  
📧 Email: your.email@example.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)  

