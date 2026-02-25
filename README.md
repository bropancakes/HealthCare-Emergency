# 🏥 HealthCare-Emergency
### Patient Health Insights: Clinical Admissions & Satisfaction Dashboard

> **A dynamic, interactive data visualization tool built to explore patient admission patterns—focusing on departmental efficiency, demographic distributions, wait-time bottlenecks, and patient experience metrics.**

---

## 📖 Project Overview
The **Patient Health Insights Dashboard** is a comprehensive Power BI report designed to analyze clinical workflows and patient experiences across **9,216 unique patient records**. This tool enables healthcare administrators to identify high-traffic departments, optimize patient wait times, and uncover correlations between admission flags and satisfaction scores to drive data-informed hospital management.

## 🛠️ Tech Stack
| Tool | Purpose |
| :--- | :--- |
| **📊 Power BI Desktop** | Core platform for data visualization and report design. |
| **📂 Power Query** | Advanced ETL, Data Wrangling, and Type Casting (fixing Locale-specific date format conflicts). |
| **🧠 DAX** | Complex measures for Average Wait Times, Satisfaction Trends, and Admission Rates. |
| **📝 Data Modeling** | Star schema design linking demographics and clinical referrals for cross-visual filtering. |
| **📁 File Format** | `.pbix` (Development) and `.csv` (Raw Data). |

## 📊 Data Source
* **Source:** Clinical Administration Dataset (`mt4w8abaHayncGoPQZpxhQ.csv`)
* **Content:** 9,216 patient logs including:
    * **Demographics:** Age, Gender, Race (White, African American, Asian, Native American).
    * **Temporal:** Admission Dates & Wait Times.
    * **Clinical:** Department Referrals, Admission Flags.
    * **Feedback:** Patient Satisfaction Scores (1-10).

---

## 💡 Features & Highlights

### ❗ Business Problem
Healthcare providers struggle to balance patient volume with quality of care. High wait times and unoptimized referrals lead to operational strain. Key questions addressed:
* Which departments are overburdened?
* Are wait times directly impacting satisfaction?
* Which demographics are most frequently admitted?

### 🎯 Goal of the Dashboard
1.  **Monitor Operational KPIs:** Track wait times and patient volume.
2.  **Segment Patient Demographics:** Identify service gaps across different groups.
3.  **Correlate Satisfaction:** Map clinical performance against patient feedback.
4.  **Strategic Forecasting:** Visualize trends for resource and staff planning.

### 🔍 Key Visuals & Metrics
* **KPI Summary:** Total Patients (**9,216**), Avg Wait Time (**35.26m**), Avg Satisfaction (**4.99/10**), Admission Rate (**50.04%**).
* **Admission Trends:** Line Chart tracking monthly inflow for seasonal preparation.
* **Departmental Rankings:** Bar Chart identifying **General Practice (1,840)** and **Orthopedics (995)** as top traffic drivers.
* **Demographic Breakdown:** Donut charts showing gender split (**51% M / 48% F**) and ethnic diversity.
* **Correlation Analysis:** Scatter/Column charts comparing wait times vs. satisfaction scores.

---

## 📈 Business Impact & Insights
* **Resource Allocation:** Data justifies increased staffing for **General Practice**, the highest-volume unit.
* **Process Optimization:** The **35-minute average wait time** serves as a baseline for "Lean Healthcare" initiatives.
* **Targeted Feedback:** Management can launch specific quality-of-care campaigns in departments with sub-5.0 satisfaction scores.
* **Capacity Planning:** Admission trends allow for better bed management and staff scheduling.

---

## 📸 Dashboard Preview

<img width="1384" alt="Healthcare Emergency Dashboard" src="https://github.com/user-attachments/assets/62ab7618-0858-4feb-931d-8ea4087d3ff4" />

---

> **Project Note:** This project demonstrates the full Data Analysis lifecycle: from resolving complex data-type conflicts (ETL) to delivering actionable business intelligence.
