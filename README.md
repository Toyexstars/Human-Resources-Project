# Human Resources Analysis


## Project Outline

[Project Overview](#project-overview)

[Data Source](#data-source)

[Tools Used](#tools-used)

[Pivot Table](#pivot-table)

[Dax Analysis](#dax-analysis)

[Visualization](#visualization)

[Result/Findings](#result-findings)

[Recommendation](#recommendation)

[Conclusion](#conclusion)

## Project Overview
This project aimed to gain an insight to the attrition of the employee based on their age, job role, department, education field and marital status.

## Data Source 
The primary source of data used is HR data.csv file and this is an open source data from Kaggle. The data contains some key columns such as:
- Atrition
- CF-age-band
- Current employee
- Gender
- Education
- Education field
- Department
- Job role
- Marital status

## Tools Used
- Microsoft Excel
  - For data cleaning
  - For Pivot Table
  - Visualization
- Power BI
 - For creating interesting report

## Pivot Table
<img width="590" alt="HR PIVOT" src="https://github.com/user-attachments/assets/8a8ea7ed-b3f8-4258-9ee8-913c2f3e3072">

- Total Employee BY	Attrition and Education field		
  ![image](https://github.com/user-attachments/assets/36c67abf-e730-48f2-a317-39a90af2fb0d)

- Total Employee BY	Attrition, Department and Gender	
![image](https://github.com/user-attachments/assets/407f220b-ed85-4cc3-850b-78e91242107c)

- Excel Visualization
  
![image](https://github.com/user-attachments/assets/fe2f62de-b5f0-4b00-9734-9b67732b873d)

## DAX Analysis
- What is the total number of employee that left the organization?
- What is the total number of current employee?
- What is the average age and marital status of the employee?
  
## KPI's (Key Performance Indicators)
1. Employee Count: Total number of employee
2. Attrition Count: Number of ex- employee
3. Current employee: Difference between the employee count and attrition
4. Attrition Rate: Attrition count divided by employee count
5. Average Age: Average of total age

## Chart Requirements
1. Total employees by Age (Donut Chart): To determine the distribution of age in the organization.
2. Total Employees by Marital Status and Gender (Barchart): To analyze categories of employee by their marital status and gender.
3. Total employees by Department (Pie Chart): To analyze percentage of employee by their department.
4. Total Employees BY Job role (Line Chart): To understand trend of employee by their job role.
5. Attrition by Department: To analyze number of employee that left the organization by department.
6. Attrition by Education Field: To analyze number of employee that left the oragnization by education field.


## Power BI Visualization

![image](https://github.com/user-attachments/assets/48c60ca4-526f-467f-a889-c46cd1376abc)


<img width="488" alt="HR Dashboard" src="https://github.com/user-attachments/assets/31c1b251-31d4-4073-926a-3970792bf459">

## Result and findings

  Based on the analysis above, the following are deduced:
  - Total employees in the organization is 1.47k, 237 employees left the organization, 16% of the total and we have 1233 current employee.
  - 673 are married, 470 are single and 327 are divorced.
  - 97 employee falls under 25 age group, 554 employee are within 25-34 age group, 505 employee are within 35-44 age group, 245 employee are within45-54 age group and 69 
    employee are over 55.
  - There are 961 employees in R&D department, 446 employee in sales department, and 63 employee in human resources department.
  - 282 employees have Associate degree, 572 employee have Bachelor's degree,170 employee have High School, 48 employee have Doctoral Degree, and 398 employees have 
    master   Degree.
  - 27 employees are in Human resources education field, 606 are in Life science education field, 159 employees are in marketing education field, 464 employees in medical 
   education field, 82 employees are in other educational field, 133 employees are in technical education field.
  - Based on the job role, there are 326 employees are sales executive, 292 are Research scientist,259 employees are Laboratory techician, 145 employees are Manufacturing 
    Director, 131 are Healthcare representative. 102 are managers, 83 emploee are Sales representative, 80 employees are Resaerch director and 62 are Human resources.

### Attrition Analysis
1. The highest number of employees are between the age 25-34 and more male gender than female.
2. R & D has the highest number of attrition by department (133 employee, 90 male and 43 female) that is 56.12%. The employees may be unsatisfied workload with and income.The Human resources has the lowest number of attrition.
3. Life science has the highest number of attrition in education field.The employees may be unsatisfied with the work environment.
4. Laboratory technician has the highest number of attrition based on job role (62 employees).
5. Employees with barchelor's degree has the number of attrition.

### Recommendation
1. Employees between the age 25-34 are active working class who are always in search of green pasture, therefore the organization should review their salary structure and also, provide on the job benefit.
2. The organization can also offer a comprehensive benefits package that addresses employee's needs, including healt insurance and retirement plan.
3. To prevent rate of attrition, the organization should promote flexible work arrangement.
4. The organization should foster a positive workplace culture and encourage open communication.

### Conclusion
By understanding the reasons employees leave and implementing proactive solutions,the  organization can improve retention rates. Promoting a positive workplace where employees feel valued can significantly reduce attrition.

