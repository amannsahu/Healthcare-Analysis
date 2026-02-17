# 🏥 Healthcare Analysis Project

## 📌 Project Overview

The **Healthcare Analysis Project** focuses on analyzing healthcare data to uncover insights related to patient behavior, hospital performance, treatment costs, and resource utilization.

The objective of this project is to leverage **data analytics tools** to improve decision-making in the healthcare domain by identifying trends, inefficiencies, and opportunities for optimization.

---

## 🎯 Objectives

* Analyze patient demographics and admission trends
* Evaluate hospital resource utilization
* Identify high treatment cost drivers
* Study disease prevalence patterns
* Provide data-driven healthcare insights

---

## 🗂️ Dataset Used

**Source:** Healthcare dataset (kaggle)

Dataset Information: Each column provides specific information about the patient, their admission, and the healthcare services provided, making this dataset suitable for various data analysis and modeling tasks in the healthcare domain. Here's a brief explanation of each column in the dataset -

1. Name: This column represents the name of the patient associated with the healthcare record.
2. Age: The age of the patient at the time of admission, expressed in years.
3. Gender: Indicates the gender of the patient, either "Male" or "Female."
4. Blood Type: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
5. Medical Condition: This column specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
6. Date of Admission: The date on which the patient was admitted to the healthcare facility.
7. Doctor: The name of the doctor responsible for the patient's care during their admission.
8. Hospital: Identifies the healthcare facility or hospital where the patient was admitted.
9. Insurance Provider: This column indicates the patient's insurance provider, which can be one of several options, including "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
10. Billing Amount: The amount of money billed for the patient's healthcare services during their admission. This is expressed as a floating-point number.
11. Room Number: The room number where the patient was accommodated during their admission. Admission Type: Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.
12. Discharge Date: The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
13. Medication: Identifies a medication prescribed or administered to the patient during their admission. Examples include "Aspirin," "Ibuprofen," "Penicillin," "Paracetamol," and "Lipitor."
14. Test Results: Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test.

---

## 🛠️ Tools & Technologies

* **SQL** → Data extraction & querying
* **Python** → Data cleaning & analysis
* **Pandas / NumPy** → Data manipulation
* **Matplotlib / Seaborn** → Visualization
* **Power BI / Excel** → Dashboard creation

---

## 🔄 Project Workflow

### 1️⃣ Data Collection

* Imported healthcare dataset from CSV format
* Loaded data into SQL / Python environment

### 2️⃣ Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized categorical fields
* Converted date columns

### 3️⃣ Data Transformation

* Created calculated fields:

  * Length of Stay
  * Cost per Day
* Aggregated department-wise metrics

### 4️⃣ Exploratory Data Analysis (EDA)

Performed analysis on:

* Patient demographics
* Disease frequency
* Admission trends
* Department workload
* Cost distribution

### 5️⃣ Visualization & Dashboard

Built interactive dashboards showing:

* Patient admissions over time
* Department performance
* Cost analysis
* Insurance vs non-insurance comparison

---

## 📊 Key Insights

* 📈 Certain diseases show higher admission rates seasonally
* 💰 Treatment costs vary significantly across departments
* 🏥 Emergency department handles the highest patient volume
* 👵 Elderly patients have longer average hospital stays
* 🛡️ Insurance coverage reduces out-of-pocket expenses substantially

---

## 🔍 Sample Analysis Questions

* Which department has the highest patient load?
* What is the average treatment cost per disease?
* How does age impact hospitalization duration?
* Which diseases are most common?

---

## 📁 Project Structure

```
Healthcare-Analysis/
│
├── data/
│   └── healthcare_dataset.csv
│
├── notebooks/
│   └── healthcare_analysis.ipynb
│
├── dashboards/
│   └── healthcare_dashboard.pbix
│
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/Healthcare-Analysis.git
```

2. Navigate to project folder

```
cd Healthcare-Analysis
```

3. Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

4. Run Jupyter Notebook / Python script

---

## 📌 Business Impact

This analysis can help healthcare organizations to:

* Optimize hospital resource allocation
* Reduce operational costs
* Improve patient care planning
* Forecast admission demand
* Enhance insurance strategy decisions

---

## 🔮 Future Enhancements

* Predictive modeling for patient readmission
* Disease outbreak forecasting
* Cost optimization models
* Real-time healthcare dashboards

Please consider giving it a **star** on GitHub — it helps showcase my work to recruiters!
