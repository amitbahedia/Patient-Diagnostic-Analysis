This project is a Power BI March 2026 challenge organanised By Databuzz (https://www.linkedin.com/feed/update/urn:li:activity:7433893220821991424/)

# 📊 Patient Diagnostic Dashboard

## 🔍 Overview

This project focuses on transforming unstructured healthcare data into a structured analytical model and building an interactive Power BI dashboard to monitor patient health, risks, and visit patterns.

The solution enables stakeholders to track key health indicators, identify high-risk patients, and analyze patient behavior across visits for better decision-making.

---

## ❗ Problem Statement

Healthcare datasets are often complex, inconsistent, and not readily usable for analysis. In this project, the dataset was AI-generated and presented multiple challenges:

* Unstructured and inconsistent patient records
* Lack of standardized clinical metrics
* No predefined data model
* Difficulty in tracking patient health trends and risks

The goal was to clean, transform, and structure the data into a reliable analytical model, enabling accurate KPI tracking and meaningful insights into patient health and behavior.

---

## 🔄 End-to-End Workflow

1. Data was first imported into **MySQL** for initial processing
2. Data cleaning and structuring were performed using SQL
3. Analytical views were created for key use cases
4. Processed data was connected to **Power BI**
5. Further transformations, modeling, and dashboard development were completed in Power BI

---

## 🎯 Objectives

* Build a structured data model (star schema)
* Standardize health metrics (BP, Diabetes, BMI, etc.)
* Develop interactive dashboards
* Identify high-risk patient segments
* Analyze visit frequency and gaps

---

## 🛠️ Tools & Technologies

* MySQL
* Power BI


---

## 📂 Project Structure

```
patient-diagnostic-dashboard/
│
├── data/
├── dashboard/
├── images/
└── README.md
```

---

## 🧠 Data Modeling Approach

### 🔄 Data Processing Workflow

* Data was initially imported into **MySQL** for preprocessing
* Data cleaning and structuring were performed at the database level
* Processed data was then connected to **Power BI** for transformation and visualization

---

### 🗂️ Data Modeling & Structure

* Built **dim_patient** table for patient-level attributes (demographics, location)
* Created **fact_patient_symptoms** table capturing diagnoses and clinical indicators
* Developed additional fact tables for visits and diagnostics
* Implemented a **star schema model** for efficient analysis

  **Data Model**
  <img width="871" height="723" alt="image" src="https://github.com/user-attachments/assets/36be5374-7edc-493d-b782-5e23e9936e87" />


---

### 🧹 Data Cleaning & Transformation

* Removed duplicate and inconsistent patient records
* Standardized clinical metrics:

  * Blood Pressure (Systolic/Diastolic)
  * Diabetes levels
  * BMI and weight
* Handled missing/null values
* Created consistent categories for risk levels and visit groups

---

### 🧮 SQL-Based Enhancements (MySQL)

* Created analytical **views in MySQL**:

  * Patient Visit Gaps (days between visits)
  * Medication and prescription analysis
* Reduced transformation load in Power BI and improved performance

---

### ⚙️ Power BI Modeling

* Built relationships between dimension and fact tables
* Created DAX measures for KPIs:

  * Hospitalization Rate
  * Risk categorization
  * Visit frequency
* Enabled interactive filtering and drill-through analysis

---

## 📊 Dashboards & Summary

---

### 🧑‍⚕️ Patient Overview Dashboard

<img width="1286" height="751" alt="image" src="https://github.com/user-attachments/assets/ee66dde6-5741-4c59-91dc-faf65cda13e6" />


#### 🔎 Summary:

* Total Patients: **3678**
* Total Visits: **10,000**
* Avg Diabetes: **162 mg/dL**
* Avg BP: **115 / 75**
* Avg BMI: **22.3**

#### 📈 Insights:

* Balanced gender distribution
* Higher concentration in **young and elderly segments**
* Strong repeat visit behavior indicates ongoing monitoring
* Regional clustering helps identify high-demand areas

---

### 🧪 Diagnostics & Risk Monitoring Dashboard
<img width="1309" height="758" alt="image" src="https://github.com/user-attachments/assets/1656cb8d-1125-4ae6-851f-14e6b22acbec" />


#### 🔎 Summary:

* High Risk Patients: **1151**
* Hospitalization Rate: **65%**
* High BP Patients: **708**
* Pre-Diabetic Patients: **2907**

#### 📈 Insights:

* Increasing trend in high-risk visits
* Large pre-diabetic population signals future risk
* Infectious diseases like **Malaria and Viral fever** are dominant
* Strong linkage between risk indicators and hospitalization

---

### 📅 Visits & Gap Analysis Dashboard

<img width="1305" height="753" alt="image" src="https://github.com/user-attachments/assets/ace0fc76-01fa-4c35-8dd1-16e400ecba2c" />


#### 🔎 Summary:

* Tracks visit frequency and gap categories
* Highlights patient follow-up behavior
* Includes medication and prescription patterns

#### 📈 Insights:

* High number of first-time visits
* Significant gaps (3–6 months, 6+ months) indicate drop-offs
* Frequent visits align with higher risk patients
* Prescription trends align with disease patterns


  **Diagnosis Engine Dashboard**
A Diagnosis Engine Dashboard is an interactive tool that simulates clinical decision-making by allowing users to input symptoms and diagnostic parameters. Based on these inputs, it dynamically evaluates conditions and suggests the most likely disease along with recommended treatments. It enables a more analytical and data-driven approach to understanding patient diagnosis beyond static historical records.

<img width="1300" height="749" alt="image" src="https://github.com/user-attachments/assets/c7b0e0ba-19f6-40f1-b190-7c102dff46a6" />

  
  

---


## 💡 Business Value

* Enables early identification of high-risk patients
* Improves patient monitoring and engagement
* Supports data-driven healthcare decisions
* Highlights behavioral and clinical trends

---

## 🔗 Future Improvements

* Real-time data integration
* Predictive risk modeling
* Advanced drill-through capabilities
* Automated ETL pipelines

---

## ⭐ Support

If you found this project useful or insightful, consider giving it a ⭐ on GitHub.  
It helps others discover the project and motivates further improvements.

## 👤 Author

**Amit Bahedia** (https://www.linkedin.com/in/amitbahedia/)

Data Analysis and Research Professional 

---
