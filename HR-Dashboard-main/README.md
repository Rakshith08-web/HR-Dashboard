# HR Dashboard

![HR Dashboard](https://github.com/user-attachments/assets/1808f707-f35d-4d51-89b3-7282e70103da)

## Table of Contents
- [Project Background](#project-background)
- [Data Structure](#data-structure)
- [Key Findings](#key-findings)
- [Dashboard](#dashboard)
- [Recommendations](#recommendations)
---

## Project Background
Workforce data covering 8,950 employees across seven departments and eight locations was analysed to surface key HR metrics. The analysis covers workforce composition, departmental distribution, demographic trends, performance by education level, and compensation disparities across gender and role.

## Data Structure

The dataset consists of a single table with **8,950 records** covering employee-level HR data across departments, locations and roles.

| Column | Description |
|--------|-------------|
| `Employee_ID` | Unique employee identifier |
| `First Name` | Employee first name |
| `Last Name` | Employee last name |
| `Gender` | Employee gender |
| `State` | US state of employment |
| `City` | City of employment |
| `Education Level` | Highest education attained (e.g. Bachelor, Master, PhD) |
| `Birthdate` | Date of birth |
| `Hiredate` | Date of hire |
| `Termdate` | Date of termination (if applicable) |
| `Department` | Department (e.g. Operations, Finance, HR) |
| `Job Title` | Employee role |
| `Salary` | Annual salary ($) |
| `Performance Rating` | Performance classification (e.g. Good, Excellent, Needs Improvement) |
---

## Key Findings
### Workforce Overview

- 8,950 employees total — 7,984 active (89%) and 966 terminated (11%)
Termination rate is consistent across all departments at under 3% each

### Departmental & Geographic Distribution

- Operations is the largest department at 2,429 employees — 16x larger than the smallest (HR at 152)
- New York HQ employs 70% of the workforce (6,270 out of 8,950); remaining 2,680 spread across 7 branches

### Demographics & Education

- Bachelor's degree holders are the largest group at 5,416 employees (60% of workforce)
- Age group 35-44 has the highest concentration of employees at 2,764 hired across all education levels

### Performance by Education

- Bachelor's holders lead in "Good" performance with 2,706 employees
PhD holders lead in "Excellent" performance with 228 employees
- High school graduates show the most room for improvement — 618 classified as "Needs Improvement"

### Compensation & Gender

- At bachelor's level, males earn ~$9,000 more than females ($66K vs $61K)
- At master's and PhD level, females out-earn males — averaging $86K-$93K vs $80K for males
- Finance Managers are the highest paid at $125K average; HR Assistants the lowest at $60K

## Dashboard

### HR Summary Dashboard
![HR Summary](https://github.com/user-attachments/assets/eafcd202-d2b7-46df-96fc-f1a8daa9b8ad)

### HR Details Dashboard
![HR Details](https://github.com/user-attachments/assets/39ae628c-77d1-443a-9769-8598fd2f28e5)

### Recommendations

1. Address the gender pay gap at bachelor's level — males earn ~$9,000 more than females at the same education level; a salary audit and pay equity policy could close this gap
2. Invest in high school graduate development — 618 classified as "Needs Improvement"; targeted training programmes could improve performance and reduce turnover risk
3. Review HR department capacity — at only 152 employees it is the smallest department yet supports 8,950 staff; additional headcount may be needed to support workforce growth
4. Leverage PhD talent — 228 "Excellent" performers concentrated in this group; identify retention strategies to keep top performers engaged and reduce termination risk
---
