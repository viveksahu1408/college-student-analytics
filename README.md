# 🎓 College Student Analytics Dashboard

## Project Overview
Designed and built a complete Student Analytics System for **Govt. Tilak College, Katni** 
managing data of **5,000+ students and 100+ staff** across UG & PG programs.

## Problem Statement
College had no central system to track student performance, attendance, and fee collection. 
All records were maintained manually with no data-driven insights.

## Solution
Built an end-to-end analytics pipeline using Python and Power BI to generate 
actionable insights for college administration.

## Tech Stack
- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Power BI** — Interactive Dashboard
- **SQL** — Data querying
- **Data** — 5,000 students, 10 months, 6 courses
  

## Dashboard Preview
- <img width="572" height="323" alt="dashcollege1" src="https://github.com/user-attachments/assets/169f6b95-2d6f-4c25-a4aa-e7f721860a42" />

## Project Structure
college-student-analytics/
│
├── college_student_analytics.ipynb   # Main analysis notebook
├── students.csv                      # Student master data
├── attendance.csv                    # Monthly attendance records
├── avg_attendance.csv                # Student-wise avg attendance
├── marks.csv                         # Subject-wise marks data
├── college.pbix                      # Power BI dashboard file
├── college_dashboard.pdf             # Dashboard PDF export
└── charts/                           # All visualization images

## Key Findings
- **BA** has highest enrollment (1,800 students)
- **PG students** have better attendance than UG (82% vs 75%)
- **December** shows lowest attendance across all courses
- **72%** fee collection rate — 28% students have pending fees


## Key Insights Generated
- 📊 Course-wise student distribution (BA, BSc, BCom, MA, MSc, MCom)
- 📈 Monthly attendance trends with 75% threshold tracking
- ✅ Pass/Fail analysis per course and subject
- 💰 Fee collection status — 72% collected, 28% pending
- 🏆 Grade distribution across all departments
- 📉 UG vs PG attendance comparison

## KPIs Tracked
| KPI | Value |
|-----|-------|
| Total Students | 5,000 |
| Avg Attendance | 76.06% |
| Overall Pass Rate | 21.65K passes |
| Fee Collected | ₹44M |
