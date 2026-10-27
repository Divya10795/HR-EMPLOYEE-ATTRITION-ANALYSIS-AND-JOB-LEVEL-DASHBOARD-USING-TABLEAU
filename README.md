# PROJECT REPORT

# HR EMPLOYEE ATTRITION ANALYSIS AND JOB LEVEL DASHBOARD USING TABLEAU

## 1. ABSTRACT

Employee attrition is an important challenge faced by organizations because employee turnover can affect productivity, recruitment expenses, workforce stability, and overall business performance. Understanding the factors associated with employees leaving an organization helps management develop effective employee retention strategies.

This project, titled **“HR Employee Attrition Analysis and Job Level Dashboard Using Tableau,”** focuses on analyzing employee information to identify patterns in attrition and understand how employee demographics, job roles, departments, salary levels, job satisfaction, overtime, and work-life balance relate to employee turnover.

The project uses a dataset containing 1,480 employee records and 39 columns. Tableau is used to create visualizations and an interactive dashboard that presents workforce information in an understandable format. The analysis identifies employee groups with higher attrition rates and provides recommendations to support human resource management and employee retention.

## 2. INTRODUCTION

Human Resource Management plays an important role in the success of an organization. Employees contribute to organizational growth through their knowledge, skills, experience, and performance. However, when employees leave an organization, the company may face additional recruitment costs, training expenses, workload pressure, and reduced productivity.

Employee attrition refers to the reduction in an organization's workforce when employees leave their positions and are not immediately replaced or retained.

HR departments need to understand why employees leave and identify the employee groups that may require additional attention. Traditional reports may not always communicate these patterns clearly. Data visualization tools such as Tableau help convert employee data into charts, comparisons, and dashboards.

This project analyzes employee attrition data using Tableau. It examines employee demographics, departments, job levels, salary slabs, job satisfaction, overtime, and years of experience. The resulting dashboard helps users explore workforce patterns and supports data-driven HR decisions.

## 3. PROBLEM STATEMENT

Organizations may find it difficult to identify the workforce characteristics associated with employee attrition when employee information is maintained in large datasets.

Without appropriate analysis, HR managers may struggle to recognize departments with higher employee turnover, job roles that need attention, and employee groups that may benefit from improved working conditions or retention initiatives.

Therefore, this project aims to analyze employee information and present meaningful insights through a Tableau dashboard to support better workforce planning and employee retention.

## 4. OBJECTIVES OF THE PROJECT

### 4.1 Primary Objective

To analyze employee attrition patterns and develop an interactive Tableau dashboard that supports human resource decision-making.

### 4.2 Secondary Objectives

1. To analyze the overall employee attrition rate.
2. To examine attrition across different age groups and gender categories.
3. To compare employee attrition among departments and job roles.
4. To understand the relationship between overtime and employee attrition.
5. To analyze employee salary slabs and job levels.
6. To examine job satisfaction, work-life balance, and employee experience.
7. To identify employee groups that may require additional retention support.
8. To present workforce information through clear and interactive visualizations.
9. To recommend strategies for improving employee retention.

## 5. SCOPE OF THE STUDY

The scope of this project is limited to the analysis of the employee attributes available in the supplied dataset.

The study covers:

- Employee demographics, including age and gender.
- Department-wise and job-role-wise workforce analysis.
- Employee attrition status.
- Salary slabs and monthly income.
- Job satisfaction and work-life balance.
- Overtime and business travel.
- Total working years and years at the company.
- Years in the current role and with the current manager.
- Job level, education, and performance rating.

The dashboard is intended to help HR teams explore employee data, identify patterns, and support workforce planning. It does not establish the exact causes of attrition or predict which individual employees will leave.

## 6. DATASET DESCRIPTION

The project uses the uploaded file named **HR-Attrition_analysis_mock_dataset.csv**.

| Dataset detail | Description |
|---|---|
| Dataset name | HR Attrition Analysis Mock Dataset |
| Total employee records | 1,480 |
| Total columns | 39 |
| Data type | Structured employee data |
| Visualization tool | Tableau |
| Main analysis area | Employee attrition and job-level analysis |
| Dashboard file | DIVII TABLEAU dashboard.twb |

### 6.1 Important Dataset Variables

**Employee information**
- EmpID
- Age
- AgeGroup
- Gender
- MaritalStatus
- Education
- EducationField

**Job information**
- Department
- JobRole
- JobLevel
- BusinessTravel
- OverTime
- YearsAtCompany
- YearsInCurrentRole
- TotalWorkingYears
- YearsWithCurrManager

**Compensation and performance**
- MonthlyIncome
- SalarySlab
- DailyRate
- HourlyRate
- PercentSalaryHike
- PerformanceRating

**Employee experience**
- Attrition
- JobSatisfaction
- EnvironmentSatisfaction
- RelationshipSatisfaction
- WorkLifeBalance
- JobInvolvement
- TrainingTimesLastYear

These variables provide the basis for comparing employee groups and understanding workforce patterns.

## 7. TOOLS AND TECHNOLOGIES USED

### 7.1 Microsoft Excel / CSV

The dataset is available in CSV format, which can be opened using Microsoft Excel. Excel can be used for initial inspection, sorting, filtering, and checking the data before importing it into Tableau.

### 7.2 Tableau

Tableau is the primary visualization tool used in this project. It supports the creation of charts, calculated fields, KPI indicators, filters, and dashboards.

### 7.3 Data Visualization

Charts and visual summaries help users compare attrition across departments, age groups, job roles, salary categories, and other employee characteristics.

## 8. METHODOLOGY

The project follows a structured data analysis process.

### Step 1: Data Collection

The employee attrition dataset was used as the main source of information. It contains employee demographics, employment details, salary information, and attrition status.

### Step 2: Data Understanding

The dataset was examined to understand its columns, data types, categories, and possible uses for HR analysis.

### Step 3: Data Preparation

The data was checked for missing values, inconsistent categories, and potential duplicate records.

The supplied dataset has 1,480 rows and 39 columns. The `YearsWithCurrManager` field contains 57 missing values, which should be reviewed before performing analyses involving that variable.

### Step 4: Data Import

The CSV dataset was connected to Tableau Desktop. The available fields were reviewed to identify dimensions and measures suitable for the visualizations.

### Step 5: Data Analysis

Employee information was compared across multiple categories, including department, age group, job role, overtime, salary slab, and job satisfaction.

### Step 6: Visualization Development

Different worksheets were created in Tableau to present attrition and workforce patterns. The uploaded workbook includes worksheets named “ATTRITION&JOB LEVEL,” “age & education,” “age and daily rates,” “average line,” “power KPI,” and “trend line,” among others.

### Step 7: Dashboard Development

Relevant worksheets were arranged in a dashboard to bring multiple views together and make the analysis easier to understand.

### Step 8: Interpretation

The results were interpreted to identify notable attrition patterns and develop practical recommendations for HR management.

## 9. DASHBOARD DESCRIPTION

The Tableau workbook contains a collection of worksheets and a dashboard. The following sections explain the main analytical views that can be presented through the project.

### 9.1 Employee Attrition Overview

This section presents the total number of employee records and the distribution of employees who have left or remained with the organization.

It helps users understand the overall attrition situation and compare the number of employees in each attrition category.

### 9.2 Attrition and Job Level Analysis

This view examines employee attrition in relation to job levels.

It helps HR managers compare attrition patterns across organizational levels and identify categories that may require further investigation.

### 9.3 Age and Education Analysis

This analysis compares employee age groups and educational backgrounds.

It helps users understand the composition of the workforce and examine whether attrition patterns differ among demographic groups.

### 9.4 Age and Daily Rate Analysis

This view explores age-related categories alongside daily-rate information.

It supports comparisons of employee characteristics and compensation-related measures.

### 9.5 KPI Indicators

The KPI section can display key workforce measures, such as:

- Total Employees
- Employees Who Left
- Employees Retained
- Attrition Rate
- Average Monthly Income

These indicators provide a quick overview of the workforce. The exact KPIs displayed should match the calculated fields in the final dashboard.

### 9.6 Average and Trend Analysis

The average-line and trend-line worksheets can help users compare measures across categories and identify broad patterns in the data.

Because the dataset does not contain a clearly identified time-period field for tracking employee departures, a trend chart should not be described as a monthly or yearly attrition trend unless the required date information is available.

## 10. DATA ANALYSIS AND FINDINGS

The following findings are calculated from the uploaded CSV dataset.

### 10.1 Overall Employee Attrition

The dataset contains 1,480 employee records.

- Employees marked as having left: 238.
- Employees marked as not having left: 1,242.
- Overall attrition rate: 16.08%.
- Employees not marked as having left: 83.92%.

The attrition rate is calculated as:

**Attrition Rate = (Employees Who Left / Total Employees) × 100**

Attrition Rate = (238 / 1,480) × 100 = **16.08%**

This indicates that approximately 16 out of every 100 employee records are marked as attrition cases in the dataset.

### 10.2 Department-Wise Attrition

| Department | Total employees | Employees who left | Attrition rate |
|---|---:|---:|---:|
| Sales | 450 | 93 | 20.67% |
| Human Resources | 63 | 12 | 19.05% |
| Research & Development | 967 | 133 | 13.75% |

**Finding:** The Sales department has the highest attrition rate at 20.67%, followed by Human Resources at 19.05%. Research & Development has the lowest rate among the three departments, at 13.75%.

The Sales department may require further investigation into workload, incentives, job expectations, management support, and employee satisfaction. However, these results alone do not prove the reasons for attrition.

### 10.3 Age Group Analysis

| Age group | Attrition rate |
|---|---:|
| 18–25 | 35.77% |
| 26–35 | 18.99% |
| 36–45 | 9.13% |
| 46–55 | 11.84% |
| 55+ | 17.02% |

**Finding:** Employees in the 18–25 age group have the highest attrition rate, at 35.77%. The 36–45 age group has the lowest rate, at 9.13%.

This pattern suggests that the organization could examine early-career employee experiences, onboarding, training opportunities, career development, and compensation expectations.

### 10.4 Overtime Analysis

| Overtime status | Attrition rate |
|---|---:|
| Yes | 30.62% |
| No | 10.36% |

**Finding:** Employees marked as working overtime have a substantially higher attrition rate than employees not marked as working overtime.

This association suggests that HR managers should review overtime requirements, workload distribution, scheduling practices, and employee well-being. The data does not establish that overtime directly causes attrition.

### 10.5 Job Role Analysis

| Job role | Attrition rate |
|---|---:|
| Sales Representative | 39.29% |
| Laboratory Technician | 23.85% |
| Human Resources | 23.08% |
| Sales Executive | 17.63% |
| Research Scientist | 15.99% |
| Healthcare Representative | 6.82% |
| Manufacturing Director | 6.80% |
| Manager | 4.90% |
| Research Director | 2.50% |

**Finding:** Sales Representatives have the highest attrition rate among the listed job roles, at approximately 39.29%. Research Directors have the lowest rate, at 2.50%.

The organization could investigate the work conditions, performance expectations, incentives, career progression, and recruitment practices associated with roles showing higher attrition.

### 10.6 Gender Analysis

| Gender | Attrition rate |
|---|---:|
| Male | 17.00% |
| Female | 14.73% |

**Finding:** The male employee group has a higher attrition rate than the female employee group in this dataset. This is a descriptive difference and should not be interpreted as evidence that gender causes employee attrition.

### 10.7 Marital Status Analysis

| Marital status | Attrition rate |
|---|---:|
| Single | 25.42% |
| Married | 11.98% |
| Divorced | 10.88% |

**Finding:** The single employee group has the highest attrition rate among the listed marital-status categories. HR teams should interpret this pattern cautiously and focus on job-related factors rather than making assumptions about employees based on personal status.

### 10.8 Monthly Income Analysis

The average monthly income of employees marked as having left is approximately 4,812.58, compared with 6,829.29 for employees marked as not having left, in the dataset's recorded income units.

**Finding:** The group marked as having left has a lower average monthly income than the group marked as not having left. This difference may justify further investigation into salary competitiveness, job levels, experience, and career progression.

The comparison does not establish that lower income is the direct cause of attrition.

### 10.9 Years With the Current Manager

Employees marked as having left have an average of approximately 2.80 years with their current manager, compared with approximately 4.37 years among employees marked as not having left.

**Finding:** The two groups differ in their average time with the current manager. This may be useful for further analysis of management relationships, role changes, and employee experience, but it does not establish a causal relationship.

## 11. KEY INSIGHTS

The analysis highlights several important patterns:

1. The overall attrition rate is 16.08%.
2. The Sales department has the highest department-level attrition rate.
3. Employees aged 18–25 have the highest attrition rate among the age groups.
4. Employees marked as working overtime have a higher attrition rate than those not marked as working overtime.
5. Sales Representatives have the highest attrition rate among the listed job roles.
6. The average monthly income is lower in the group marked as having left.
7. The average time with the current manager is lower in the group marked as having left.

These findings can help HR teams identify areas for additional investigation and employee retention planning.

## 12. RECOMMENDATIONS

Based on the descriptive analysis, the following actions may be considered.

### 12.1 Improve Employee Retention

Develop employee retention initiatives for departments and job roles that show higher attrition rates. Conduct exit interviews and employee feedback surveys to understand the reasons behind departures.

### 12.2 Support Early-Career Employees

Provide structured onboarding, mentoring, training, career guidance, and regular feedback for early-career employees.

### 12.3 Review Overtime Practices

Assess workload distribution, overtime frequency, staffing levels, and work schedules. Encourage managers to identify excessive workloads and improve work-life balance.

### 12.4 Review Compensation and Career Growth

Compare salary structures and career progression opportunities across roles and experience levels. Use additional evidence before changing compensation policies.

### 12.5 Strengthen Manager Support

Encourage regular one-to-one discussions, constructive feedback, recognition, and professional development planning between managers and employees.

### 12.6 Monitor Attrition KPIs

Review attrition indicators regularly and compare departments, job roles, age groups, and other relevant employee categories. Where reliable departure dates are available, monitor changes over time.

### 12.7 Use Data Responsibly

Use the dashboard to support fair and evidence-based HR decisions. Avoid making employment decisions about individuals based solely on demographic categories or descriptive patterns.

## 13. LIMITATIONS OF THE STUDY

1. The project is based on the supplied mock dataset and may not represent the workforce of a real organization.
2. The analysis uses the available employee attributes and does not establish causal relationships.
3. The dataset contains 57 missing values in the `YearsWithCurrManager` field.
4. The dataset does not provide a clearly identified departure-date field for a reliable monthly or yearly attrition trend.
5. The analysis is descriptive and does not include a validated predictive model.
6. The accuracy of the findings depends on the quality and consistency of the supplied data.
7. The dashboard findings should be validated with additional organizational information before making business decisions.

## 14. FUTURE SCOPE

The project can be enhanced in several ways:

- Integrate updated employee records to monitor attrition over time.
- Add monthly or yearly attrition analysis when departure dates are available.
- Develop more detailed department-wise and job-role-wise dashboards.
- Add interactive filters for age, department, job level, salary slab, and overtime.
- Compare attrition with employee satisfaction and performance measures.
- Integrate Power BI or other reporting tools where required.
- Develop a machine-learning model to estimate attrition risk, using appropriate validation and responsible data practices.
- Connect the dashboard to a regularly updated data source for ongoing HR monitoring.

## 15. CONCLUSION

The project, **“HR Employee Attrition Analysis and Job Level Dashboard Using Tableau,”** demonstrates how employee data can be transformed into meaningful visual insights to support human resource management.

The analysis of 1,480 employee records identifies an overall attrition rate of 16.08%. Higher attrition rates are observed among employees in the Sales department, employees aged 18–25, employees marked as working overtime, and employees in the Sales Representative role.

The findings also show differences in average monthly income and time with the current manager between employees marked as having left and those marked as not having left.

Tableau provides an effective way to communicate these patterns through charts, KPI indicators, and an interactive dashboard. The project can help HR teams identify areas that require further investigation, improve workforce monitoring, and plan appropriate employee retention initiatives.

Overall, the project demonstrates the practical value of data analysis and visualization in HR decision-making. The findings should be treated as descriptive insights rather than proof of the causes of attrition.

## 16. REFERENCES

1. HR-Attrition_analysis_mock_dataset.csv — supplied project dataset.
2. DIVII TABLEAU dashboard.twb — supplied Tableau workbook.
3. Tableau Desktop — data visualization and dashboard development software.
4. Microsoft Excel — spreadsheet software for data inspection and preparation.
5. Official Tableau learning resources — documentation on worksheets, calculated fields, charts, and dashboards.

