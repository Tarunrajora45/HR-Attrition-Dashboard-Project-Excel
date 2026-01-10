# 🧑‍💼📉 HR-Attrition-Dashboard-Project-Excel
---
# Table of Contents

### <a href="#-project-overview">Overview</a>
### <a href="#-corporate-workforce-problems-solved">Problems Solved</a>
### <a href="#-why-this-project-stands-out">Why this Project Stand out ?</a>
### <a href="#repository-structure">Repository Structure</a>
### <a href="Dashboard/HR-Employee-Attrition%20And%20Head%20Count%20Project%20Report.xlsx">Dashboard</a>
### <a href="Data/Raw%20Dataset.csv">Dataset</a>
### <a href="Preview/">Dashboard Preview</a>
### <a href="#-dashboard-overview-executive-layer">Dashboard Structure</a>
### <a href="#%EF%B8%8F-data-preparation--calculations">Data Preparation</a>
### <a href="#-project-structure">Project Structure</a>
### <a href="#-key-project-insights">Project Insights</a>
### <a href="#-key-project-highlights">Project Highlights</a>
### <a href="#-tools--skills-used">Tools & Skills used</a>
### <a href="#-helping-feedback--recommendations">Feedback Recommendation</a>
### <a href="#created-by">Created By</a>
---
# 📌 Project Overview

- This HR Employee Attrition & Headcount Analytics Project is Built on 1,470 employee records, this project combines Power Query–based data transformation, calculated fields, and pivot-driven analytics to move beyond static HR reporting. 
- The dashboard enables HR leaders to explore how department, education level, gender, business travel, tenure, overtime, and career progression interact to influence employee exits.
- Rather than asking “How many employees left?”, this project focuses on:
Who is leaving, from where, under what conditions, and why?
---

# 🏢 Corporate Workforce Problems Solved
##  1️⃣ Burnout Masked as Productivity (Overtime Risk)
### Problem:
- Overtime is often normalized as commitment, masking early burnout signals.
### What This Project Reveals:
- Attrition among overtime employees is significantly higher, confirming overtime as a predictive attrition driver, not a productivity advantage.

## 2️⃣ Role & Department-Level Attrition Blind Spots
### Problem:
- Aggregate attrition numbers hide where talent loss is actually concentrated.
### What This Project Solves:
- By breaking attrition down by department and job role, HR can identify:
Sales as a high-risk function
Specific job roles acting as churn epicenters. 

## 3️⃣ Career Stagnation & Promotion Delays
### Problem:
- Employees often leave not because of pay, but because of stalled growth.
### What This Project Reveals:
- Attrition trends increase with years since last promotion, highlighting promotion velocity as a key retention lever.

## 4️⃣ Attrition Numbers Without Context Lead to Wrong Decisions
### Problem:
- Treating all exits as equal often leads to reactive decisions such as blanket hiring or misallocated HR budgets—because leadership lacks context on who is leaving and why.
### What This Project Solves:
- This dashboard adds context to attrition by analyzing exits across department, gender,job role and linking them with overtime, promotion gaps, tenure, and engagement drivers.

---
# 🌟 Why This Project Stands Out?
- Focuses on diagnostic HR analytics, not surface reporting
- Combines behavioral, demographic, and structural drivers
- Uses Power Query + Pivot logic, not manual analysis
- Designed for HR leaders, not just analysts
Links people decisions to business continuity and cost. 

---
# Repository Structure
```
📦 HR-Employee-Attrition-And-Headcount-Analytics
 ┣ 📂 Dashboard
 ┃ ┗ 📊 HR-Employee-Attrition-And-Head-Count-Project-Report.xlsx
 ┣ 📂 Data
 ┃ ┗ 📄 Raw Dataset.csv
 ┣ 📂 Preview
 ┃ ┣ 🖼 01_HR-attrition-by-department-age-gender-job-role.png
 ┃ ┣ 🖼 02_HR-attrition-by-promotion-overtime-exit-trends.png
 ┃ ┗ 🖼 03_HR-attrition-by-experience-drivers.png
 ┗ 📄 README.md

```
---
# 📊 Dashboard Overview (Executive Layer)
![Kpi Dashboard](Preview/01_Hr.attrition%20by%20department%2Cage%2Cgender%20%26%20Job%20role.png)

## The KPI section : 
- Total Employees – Raw headcount
- Active Employees –
Absolute number
,Percentage of total workforce
- Exited Employees –
Absolute number
, Attrition percentage
- Average Tenure – In years
- Average Age – Workforce demographic indicator
All KPIs update dynamically based on slicer selections.

## 🎛 Filters & Interactivity (Slicers)
- The dashboard includes four slicers only, intentionally chosen for strategic relevance:
- Department
- Education Level
- Gender
- Business Travel
- These slicers allow HR leaders to simulate real investigative scenarios such as:
Attrition among frequent travelers
Gender-based exit patterns within departments
Education-level retention risks

## 📈 Charts & Visual Analysis
### 1️⃣ Attrition by Department (Pie Chart)
- Sales
- Research & Development
- Human Resources
- ➡️ Shows proportional contribution to total attrition.
### 2️⃣ Attrition by Age Group & Gender (Dual-Color column Chart)
- Age buckets and gender(Male / Female)
- ➡️ Highlights demographic cohorts with elevated exit risk.
### 3️⃣ Attrition by Job Role (Tree Map)
- Visualizes churn concentration across job roles
- ➡️ Instantly identifies high-impact roles

![2nd Attrition](Preview/02_Hr.attrition%20by%20promoyion%2Covertime%20%26%20exit%20trends.png)

### 4️⃣ Attrition by Years Since Last Promotion (Line Chart)
- Tracks attrition trend as promotion gaps widen
- ➡️ Direct insight into career stagnation risk
### 5️⃣ Attrition by Overtime (Donut Chart)
- Compares overtime vs non-overtime employees
- ➡️ Reinforces overtime as a structural attrition driver
### 6️⃣ Attrition Trend Over Time (Line Chart)
- Exit patterns across year buckets
- ➡️ Helps identify periods of organizational instability

![3rd Attritiopn](Preview/03_Hr.attrition%20by%20experirence%20drivers.png)

### 7️⃣ Employee Experience Drivers (Primary Diagnostic Section)
- A large, consolidated analysis card featuring four horizontal charts:
- ✅ Job Satisfaction
- ✅ Performance Rating
- ✅ Work-Life Balance
- ✅ Job Involvement
#### This section acts as the core behavioral diagnosis layer, revealing whether attrition is driven by:
- 🔻Disengagement
- 🔻 Performance pressure
- 🔻 Work-life imbalance
- 🔻 Low role involvement
- ➡️ All visuals respond dynamically to slicers.

---
# ⚙️ Data Preparation & Calculations
## Data Transformation
- Data cleaned and shaped using Power Query
Removed inconsistencies and standardized categorical fields
- Engineered age groups and years buckets.
## Calculations
- Attrition flags (Exited with red and white formatting)
- Attrition percentages via pivot calculations
- Average age and tenure using calculated fields
- KPI metrics derived from pivot logic and formulas. 

---
# 📂 Project Structure 
```
Raw Employee Data
        ↓
Power Query Cleaning & Transformation
        ↓
Calculated Fields & Pivot Metrics
        ↓
Dynamic KPIs & Visuals
        ↓
Slicer-Driven Workforce Analysis

```
---

# 🔍 Key Project Insights 
- Overtime is a leading attrition accelerator
- Sales roles face disproportionate churn risk
- Mid-career and promotion-delayed employees are vulnerable
- Engagement metrics explain exits better than demographics alone

---

# 🏆 Key project Highlights 
- Total employees :- 1470
- Active employees :- 1233, 84%
- Exited employees :- 237, 16%
- Average age :- 37
- Average tenure :- 7
- Overtime vs no overtime :- 56% vs 46%

---
# 🛠 Tools & Skills Used
- Microsoft Excel
- Pivot Tables & Pivot Charts
- HR Metrics & Attrition Analysis
- Conditional Logic & Calculated Fields 
- Dashboard Design Principles

---
# 💬 Helping Feedback & Recommendations
- Your Feedback & Critics means a lot to me . feel free to collaborate & giving feedback or asking questions on this project. I really appreciate every critic & great idea , feel free to reach out .

---
# Created By
- 🙋‍♂️ Tarun Rajora
- 📞 +91 8218-228575 
- 📧 <a href="mailto:trajora106@gnmail.com">trajora106@gmail.com</a>
- 🔗 <a href="https://www.linkedin.com/in/tarun-rajora-1531332a1/">Linkedin</a>
