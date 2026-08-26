# 💡 HR Analytics Business Insights

## 📌 Overview

This document summarizes the key business insights obtained from the analysis of the IBM HR Analytics Employee dataset using Python.

The analysis focuses on employee attrition, overtime, compensation, satisfaction, job roles, departments, and employee experience.

---

## 📉 Attrition Insights

### Overall Attrition

The dataset contains **1,470 employees**.

- Employees who stayed: **1,233**
- Employees who left: **237**
- Overall attrition rate: **16.12%**

This indicates that approximately one out of every six employees in the dataset left the organization.

### Attrition by Department

The analysis shows differences in attrition across departments.

- **Sales** has a higher attrition rate than Research & Development.
- **Human Resources** also shows relatively high attrition.
- **Research & Development** has a comparatively lower attrition rate.

This suggests that retention strategies may need to be tailored to individual departments.

### Attrition by Job Role

Some job roles show substantially higher attrition than others.

The highest attrition is observed among roles such as:

- Sales Representatives
- Laboratory Technicians
- Human Resources
- Sales-related positions

Lower attrition is generally observed in several senior and specialized roles.

This indicates that job role and career structure can influence employee retention.

---

## ⏰ Overtime and Attrition

Overtime is strongly associated with employee attrition.

Employees working overtime have a considerably higher attrition rate than employees who do not work overtime.

The analysis shows approximately:

- **Overtime = Yes:** 30.53% attrition
- **Overtime = No:** 10.44% attrition

This indicates that excessive overtime may be an important employee-retention risk factor.

### Business Interpretation

Organizations should monitor employee workloads and overtime levels to reduce burnout and improve employee retention.

---

## 💰 Compensation Insights

The analysis compares monthly income across job roles and employee attrition status.

Higher-level positions generally have higher monthly income, while entry-level and operational positions tend to have lower compensation.

The analysis also compares compensation between employees who stayed and employees who left.

### Business Interpretation

Compensation should be evaluated together with job level, role, experience, and attrition because salary differences alone may not explain employee turnover.

---

## 😊 Employee Satisfaction Insights

Employee satisfaction was analyzed using:

- Job Satisfaction
- Environment Satisfaction
- Relationship Satisfaction
- Work-Life Balance
- Job Involvement

The analysis shows that employees who left generally have lower average satisfaction scores than employees who stayed.

### Average Satisfaction Comparison

| Metric | Stayed | Left |
|---|---:|---:|
| Job Satisfaction | 2.77 | 2.47 |
| Environment Satisfaction | 2.77 | 2.46 |
| Relationship Satisfaction | 2.85 | 2.60 |
| Work-Life Balance | 2.78 | 2.66 |

### Business Interpretation

Lower satisfaction among employees who left suggests that improving workplace experience, employee engagement, and work-life balance may support better retention.

---

## 📈 Experience & Tenure Insights

The analysis examines:

- Total Working Years
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager

### Average Experience Comparison

| Metric | Stayed | Left |
|---|---:|---:|
| Total Working Years | 7.29 | 7.10 |
| Years at Company | 7.37 | 5.13 |
| Years in Current Role | 4.48 | 2.90 |
| Years Since Last Promotion | 2.23 | 1.95 |
| Years With Current Manager | 4.37 | 2.85 |

### Business Interpretation

Employees who left generally had fewer years at the company, fewer years in their current role, and fewer years with their current manager.

This suggests that early-tenure employees may require stronger onboarding, career development, mentoring, and engagement initiatives.

---

## 👥 Workforce Insights

The analysis examines employee characteristics across:

- Departments
- Job Roles
- Job Levels
- Education
- Age
- Gender
- Marital Status
- Business Travel

These workforce characteristics help identify employee groups that may require targeted HR strategies.

---

## 🎯 Key Business Findings

The analysis highlights several important findings:

1. The overall employee attrition rate is **16.12%**.
2. Employees working overtime have substantially higher attrition than employees who do not work overtime.
3. Attrition varies significantly across departments and job roles.
4. Sales Representatives and several operational roles show relatively high attrition.
5. Employees who leave generally report lower satisfaction scores.
6. Employees who leave tend to have shorter organizational tenure.
7. Employees who leave generally have fewer years in their current role.
8. Employees who leave generally have fewer years with their current manager.
9. Compensation varies considerably across job roles and job levels.
10. Employee retention is influenced by a combination of workload, satisfaction, career progression, role, and tenure.

---

## 💡 HR Recommendations

Based on the analysis, the following actions can be considered:

### 1. Reduce Excessive Overtime

Monitor overtime levels and identify teams experiencing consistently high workloads.

### 2. Strengthen Employee Retention

Develop targeted retention programs for departments and job roles with higher attrition.

### 3. Improve Employee Satisfaction

Conduct regular employee feedback surveys and address workplace concerns related to satisfaction and work-life balance.

### 4. Support Career Development

Provide clear career progression paths, training opportunities, mentoring, and internal mobility programs.

### 5. Focus on Early-Tenure Employees

Strengthen onboarding and mentoring programs for employees in the early stages of their careers.

### 6. Review Compensation

Regularly evaluate compensation across roles, experience levels, and job levels to maintain competitive and fair pay structures.

### 7. Improve Manager-Employee Relationships

Encourage effective communication and mentoring between managers and employees.

---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Employees | 1,470 |
| Employees Stayed | 1,233 |
| Employees Left | 237 |
| Overall Attrition Rate | 16.12% |
| Attrition with Overtime | 30.53% |
| Attrition without Overtime | 10.44% |

---

## 🔎 Analysis Areas

The project covers the following areas:

- Employee attrition
- Department analysis
- Job role analysis
- Overtime analysis
- Compensation analysis
- Employee satisfaction
- Work-life balance
- Employee experience
- Employee tenure
- Workforce characteristics

---

## 🧠 Analytical Approach

The analysis was performed using Python with:

- Pandas
- NumPy
- Matplotlib
- Seaborn

The workflow included:

1. Loading the HR dataset
2. Understanding the dataset structure
3. Checking data quality
4. Analyzing employee attrition
5. Comparing departments and job roles
6. Analyzing overtime
7. Examining compensation
8. Evaluating employee satisfaction
9. Studying employee experience and tenure
10. Extracting business insights
11. Developing HR recommendations

---

## 📁 Project Resources

- `HR_Analytics_Analysis.ipynb` — Complete Python analysis
- `data/` — HR analytics dataset
- `insights/business_insights.md` — Business findings and recommendations
- `requirements.txt` — Python dependencies

---

## 📌 Conclusion

The analysis demonstrates that employee attrition is influenced by multiple workforce factors rather than a single variable.

Overtime, job role, department, employee satisfaction, and organizational tenure show meaningful relationships with employee attrition.

The findings can help HR teams identify potential retention risks and develop targeted strategies to improve employee engagement and workforce stability.

---

## 👩‍💻 Author

**Sanapala Bhargavi**

Aspiring Data Analyst

### 🔗 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/bhargavi-sanapala-bbb4952a8)
- [GitHub](https://github.com/Sanapalabhargavi)
- Email: bhargavisanapala7@gmail.com

---

## ⭐ Project Status

**Completed — Analysis and business insights documented**

This project demonstrates practical skills in Python, Pandas, NumPy, exploratory data analysis, data visualization, and business analytics.
