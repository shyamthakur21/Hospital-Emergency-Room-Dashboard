# 🏥 Hospital Emergency Room Dashboard

An interactive **Hospital Emergency Room Dashboard** created using **Microsoft Excel** to analyze patient flow, waiting time, satisfaction score, admission status, demographics, age groups, attendance status, and department referrals.

This project transforms hospital emergency-room data into an easy-to-understand and interactive dashboard for **healthcare data analysis and reporting**.

---

## 📊 Dashboard Preview

![Hospital Emergency Room Dashboard](Hospital%20Emergency%20Room.png)

---

## 🎯 Project Objective

The main objective of this project is to analyze **Emergency Room (ER) performance** and present important healthcare information through an interactive Excel dashboard.

The dashboard helps answer questions such as:

- How many patients visited the emergency room?
- What is the average patient waiting time?
- What is the average patient satisfaction score?
- How many patients were admitted or not admitted?
- What is the gender distribution of patients?
- Which age group has the highest number of patients?
- Which departments receive the most patient referrals?
- What percentage of patients were on-time or delayed?
- How does the data change between different years?

---

## 📌 Key Performance Indicators (KPIs)

The dashboard contains three major KPI cards:

| KPI | Value |
|---|---:|
| 👥 **No. of Patients** | **431** |
| ⏱️ **Average Wait Time** | **36.67 Minutes** |
| ⭐ **Patient Satisfaction Score** | **4.72** |

These KPIs provide a quick overview of the emergency-room performance.

---

## 📈 Dashboard Analysis

### 1️⃣ Patient Attend Status

The dashboard uses a **Doughnut Chart** to display patient attendance status.

- **Delay:** 66%
- **On-time:** 34%

This visualization provides a quick comparison between patients who experienced delays and those who were attended on time.

---

### 2️⃣ Gender-wise Analysis

A **Doughnut Chart** is used to show the gender distribution of patients.

- **Male:** 55%
- **Female:** 45%

This helps understand the gender composition of patients visiting the emergency room.

---

### 3️⃣ Admission Status

The dashboard displays the number and percentage of admitted and non-admitted patients.

| Admission Status | Patients | Percentage |
|---|---:|---:|
| **Not Admitted** | 494 | 52.11% |
| **Admitted** | 454 | 47.89% |

A horizontal bar visualization is also used to make the comparison easier.

---

### 4️⃣ Patient Age Group Analysis

A **Column Chart** shows the number of patients across different age groups.

| Age Group | Patients |
|---|---:|
| 0–09 | 42 |
| 10–19 | 46 |
| 20–29 | 54 |
| 30–39 | 68 |
| 40–49 | 62 |
| 50–59 | 52 |
| 60–69 | 54 |
| 70–79 | 53 |

The **30–39 age group** has the highest number of patients among the displayed age groups.

---

### 5️⃣ Department Referral Analysis

A **Horizontal Bar Chart** displays the number of patients referred to different departments.

The dashboard includes:

- **None:** 252
- **General Practice:** 89
- **Orthopedics:** 46
- **Physiotherapy:** 14
- **Cardiology:** 12
- **Renal:** 6
- **Gastroenterology:** 6
- **Neurology:** 6

This visualization helps identify the departments receiving patient referrals from the emergency room.

---

### 6️⃣ Year Filter

The dashboard includes an interactive **Year Filter** with:

- **2023**
- **2024**

The year selection allows the user to change the reporting period and analyze the dashboard data accordingly.

---

## 🛠️ Tools & Technologies

This project was created using:

- **Microsoft Excel**
- **Excel Pivot Tables**
- **Excel Charts**
- **Excel Slicers / Filters**
- **Excel Formulas**
- **Data Cleaning**
- **Data Analysis**
- **Data Visualization**

---

## 🔄 Project Workflow

```text
Raw Hospital Data
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Pivot Table Analysis
       ↓
KPI Calculations
       ↓
Charts & Visualizations
       ↓
Interactive Excel Dashboard
       ↓
Healthcare Insights
```

Dataset Information

The dataset contains important emergency-room patient information such as:

Patient ID
Patient Admission Date
Patient Admission Time
Patient Gender
Patient Age
Patient Race
Department Referral
Patient Admission Status
Patient Satisfaction Score
Patient Wait Time
Patient Age Group
Patient Attendance Status

These fields were used to create the dashboard analysis and visualizations.

📐 Important Metrics
Total Patients
Total Patients = Count of Patient ID
Average Wait Time
Average Wait Time = Average of Patient Wait Time
Average Satisfaction Score
Average Satisfaction = Average of Patient Satisfaction Score
Admission Rate
Admission Rate = Admitted Patients / Total Patients × 100

These calculations were used to create the important KPIs and dashboard analysis in Excel.

💡 Key Insights
431 patients are shown in the main dashboard KPI.
The average patient waiting time is 36.67 minutes.
The patient satisfaction score is 4.72.
66% of patients were marked as delayed, while 34% were on-time.
The gender distribution consists of 55% male and 45% female patients.
The dashboard shows 494 non-admitted and 454 admitted patients in the admission analysis.
The 30–39 age group has the highest number of patients among the displayed age groups.
None is the largest category in department referral, followed by General Practice and Orthopedics.
The dashboard provides year-wise filtering for 2023 and 2024.
📁 Project Files
Hospital-Emergency-Room-Dashboard/
│
├── Hospital Dashboard.xlsx
├── Hospital Emergency Room.png
└── README.md
