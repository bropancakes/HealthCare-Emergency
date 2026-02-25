# HealthCare-Emergency

🏥 Patient Health Insights: Clinical Admissions & Satisfaction Dashboard
A dynamic, interactive data visualization tool built to explore patient admission patterns—focusing on departmental efficiency, demographic distributions, wait-time bottlenecks, and patient experience metrics.

2. Short Description / Purpose
The Patient Health Insights Dashboard is a comprehensive Power BI report designed to analyze clinical workflows and patient experiences across 9,216 unique patient records. This tool enables healthcare administrators to identify high-traffic departments, optimize patient wait times, and uncover correlations between admission flags and satisfaction scores to drive data-informed hospital management.

3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for data visualization and report design.

📂 Power Query – Used for advanced ETL, including Data Wrangling and Type Casting (fixing Locale-specific date format conflicts).

🧠 DAX (Data Analysis Expressions) – Implemented for complex measures such as Average Wait Times, Satisfaction Trends, and Admission Rates.

📝 Data Modeling – Star schema design linking demographics, clinical referrals, and satisfaction scores for cross-visual filtering.

📁 File Format – .pbix for the development file and .csv for the raw dataset.

4. Data Source
Source: Clinical Administration Dataset (mt4w8abaHayncGoPQZpxhQ.csv).

Content: Detailed logs of 9,216 patient visits, including demographics (Age, Gender, Race), temporal data (Admission Dates), clinical details (Department Referrals, Admission Flags), and feedback (Satisfaction Scores).

5. Features / Highlights
• Business Problem
Healthcare providers often struggle to balance patient volume with quality of care. High wait times and unoptimized department referrals lead to decreased patient satisfaction and operational strain. Key questions like: Which departments are overburdened? Are wait times affecting satisfaction? Which demographics are most frequently admitted? are difficult to extract from raw logs.

• Goal of the Dashboard
To deliver an interactive diagnostic tool that:

Monitors Operational KPIs (Wait Times & Volume).

Segments Patient Demographics to identify service gaps.

Correlates Patient Satisfaction with clinical performance metrics.

Visualizes Admission Trends to help in resource and staff forecasting.

• Walkthrough of Key Visuals
Key KPIs (Top Summary):

Total Patient Records: 9,216

Average Wait Time: 35.26 Minutes

Average Satisfaction Score: 4.99 / 10

Admission Rate: 50.04%

Admission Trend over Time (Line Chart): Tracks patient inflow by month, identifying peak admission periods for seasonal preparation.

Top Departments by Referral (Bar Chart): Ranks the 7 core departments, highlighting General Practice (1,840) and Orthopedics (995) as the highest-traffic areas.

Patient Demographic Breakdown (Pie/Donut Charts): Visualizes the balanced gender distribution (51% Male, 48% Female) and ethnic diversity within the patient population.

Wait Time vs. Satisfaction (Correlation Chart): Analyzes if higher wait times (averaging 35 mins) directly lead to lower satisfaction scores.

Departmental Wait-Time Analysis (Column Chart): Compares average delays across specialized units like Cardiology and Neurology to pinpoint operational bottlenecks.

• Business Impact & Insights
Resource Allocation: By identifying General Practice as the highest-volume department, management can justify increased staffing in that unit.

Process Optimization: Spotlighting the 35-minute average wait time provides a baseline for "Lean Healthcare" initiatives to reduce delays.

Patient Satisfaction: Insights into the ~5.0 satisfaction score allow the hospital to launch targeted feedback campaigns in low-scoring departments.

Strategic Forecasting: Admission trends allow administrators to predict high-volume months and manage bed capacity effectively.

6. Screenshots / Demos
  
<img width="1384" height="846" alt="Healthcare Emergency&#39;" src="https://github.com/user-attachments/assets/62ab7618-0858-4feb-931d-8ea4087d3ff4" />


This project demonstrates the full Data Analysis lifecycle: from resolving complex data-type conflicts (ETL) to delivering actionable business intelligence.
# HealthCare-Emergency

🏥 Patient Health Insights: Clinical Admissions & Satisfaction Dashboard
A dynamic, interactive data visualization tool built to explore patient admission patterns—focusing on departmental efficiency, demographic distributions, wait-time bottlenecks, and patient experience metrics.

2. Short Description / Purpose
The Patient Health Insights Dashboard is a comprehensive Power BI report designed to analyze clinical workflows and patient experiences across 9,216 unique patient records. This tool enables healthcare administrators to identify high-traffic departments, optimize patient wait times, and uncover correlations between admission flags and satisfaction scores to drive data-informed hospital management.

3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for data visualization and report design.

📂 Power Query – Used for advanced ETL, including Data Wrangling and Type Casting (fixing Locale-specific date format conflicts).

🧠 DAX (Data Analysis Expressions) – Implemented for complex measures such as Average Wait Times, Satisfaction Trends, and Admission Rates.

📝 Data Modeling – Star schema design linking demographics, clinical referrals, and satisfaction scores for cross-visual filtering.

📁 File Format – .pbix for the development file and .csv for the raw dataset.

4. Data Source
Source: Clinical Administration Dataset (mt4w8abaHayncGoPQZpxhQ.csv).

Content: Detailed logs of 9,216 patient visits, including demographics (Age, Gender, Race), temporal data (Admission Dates), clinical details (Department Referrals, Admission Flags), and feedback (Satisfaction Scores).

5. Features / Highlights
• Business Problem
Healthcare providers often struggle to balance patient volume with quality of care. High wait times and unoptimized department referrals lead to decreased patient satisfaction and operational strain. Key questions like: Which departments are overburdened? Are wait times affecting satisfaction? Which demographics are most frequently admitted? are difficult to extract from raw logs.

• Goal of the Dashboard
To deliver an interactive diagnostic tool that:

Monitors Operational KPIs (Wait Times & Volume).

Segments Patient Demographics to identify service gaps.

Correlates Patient Satisfaction with clinical performance metrics.

Visualizes Admission Trends to help in resource and staff forecasting.

• Walkthrough of Key Visuals
Key KPIs (Top Summary):

Total Patient Records: 9,216

Average Wait Time: 35.26 Minutes

Average Satisfaction Score: 4.99 / 10

Admission Rate: 50.04%

Admission Trend over Time (Line Chart): Tracks patient inflow by month, identifying peak admission periods for seasonal preparation.

Top Departments by Referral (Bar Chart): Ranks the 7 core departments, highlighting General Practice (1,840) and Orthopedics (995) as the highest-traffic areas.

Patient Demographic Breakdown (Pie/Donut Charts): Visualizes the balanced gender distribution (51% Male, 48% Female) and ethnic diversity within the patient population.

Wait Time vs. Satisfaction (Correlation Chart): Analyzes if higher wait times (averaging 35 mins) directly lead to lower satisfaction scores.

Departmental Wait-Time Analysis (Column Chart): Compares average delays across specialized units like Cardiology and Neurology to pinpoint operational bottlenecks.

• Business Impact & Insights
Resource Allocation: By identifying General Practice as the highest-volume department, management can justify increased staffing in that unit.

Process Optimization: Spotlighting the 35-minute average wait time provides a baseline for "Lean Healthcare" initiatives to reduce delays.

Patient Satisfaction: Insights into the ~5.0 satisfaction score allow the hospital to launch targeted feedback campaigns in low-scoring departments.

Strategic Forecasting: Admission trends allow administrators to predict high-volume months and manage bed capacity effectively.

6. Screenshots / Demos
  
<img width="1384" height="846" alt="Healthcare Emergency&#39;" src="https://github.com/user-attachments/assets/62ab7618-0858-4feb-931d-8ea4087d3ff4" />


This project demonstrates the full Data Analysis lifecycle: from resolving complex data-type conflicts (ETL) to delivering actionable business intelligence.
