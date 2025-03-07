# **Green Destinations - Employee Attrition Analysis**
I developed a comprehensive project in Power BI, creating multiple dashboards and tables to analyze the data. This process involved several stages, including data preprocessing, data cleaning, and data visualization.
 
## **Introduction** 
Green Destinations, a well-known travel agency, is experiencing an increase in employee attrition (employees leaving the company). The HR Director wants to analyze this trend to identify any patterns or contributing factors. To facilitate this analysis, a survey has been conducted among the staff, and data has been provided for review. ### **Objectives of the Project** 
1. **Determine the attrition rate** – Calculate the percentage of employees who have left.
2. **Identify influencing factors** – Analyze whether factors like age, years at the company, and income impact employee attrition. The findings from this analysis will help the HR Director understand employee turnover trends and possibly take corrective measures to improve retention. ---
## **Dataset Used**
-<a href="https://github.com/maria-vensa/Greendestinations_HR-Analytics/blob/main/greendestination%20(1).csv">Dataset</a>

## **Key Performance Indicators (KPIs)** 
Here are the key performance indicators (KPIs) framed as question statements: - 
- What is the attrition count based on gender?
- How does attrition vary across different education levels?
- What is the attrition rate for different age groups?
- How does attrition correlate with years spent in the current role?
- What is the attrition rate based on salary slabs?
- What is the percentage salary hike among employees who left versus those who stayed?
- How does age impact employee attrition?
- Which job roles have the highest attrition rates?
- ### **Attrition Count Categorized by:**
- - Gender
  - Education
  - Age Group
  - Years in Current Role
  - Salary Slab
  - Percentage Salary Hike
  - Age
  - Job Role
  ## **Process**
    1. Verify data for any missing values and anomalies (name errors/spelling errors), and rectify them.
    2. Check the datatypes of each column.
    3. Create a new age group column for better analysis.
    4. Create a new measure for attrition rate calculation.

       Attrition Rate = SUM('HR analytics'[Attrition Count])/SUM('HR analytics'[EmployeeCount])
  ## **Dashboard**
    -<a href="https://github.com/maria-vensa/Greendestinations_HR-Analytics/blob/main/dashboard%20pic.png">Dashboard</a>
  
  ## **Project Insights & Recommendations**

  ## **Project Insights**
  - **Highest attrition** in **Life Sciences (37.55%)** and **Medical (26.58%)** fields.
  - Majority of employees leaving are aged **26-35 (606 employees)** and **36-45 (468 employees)**.
  - **Younger employees (18-25) and older employees (55+)** have lower attrition numbers.
  - Employees with **0-2 years in the current role** have the highest attrition (**244 + 392 employees**).
  - **Attrition significantly drops** after **3 years** in the same role.
  - Employees earning **up to 5K** have the highest attrition (**749 employees**).
  - **Attrition decreases** as salary increases, with **only 133 employees** leaving from the **15K+ salary 
     range**.
  - Higher attrition is observed among employees who received **lower salary hikes (0-10%)**.
  - **Attrition drops significantly** with **higher percentage salary hikes**.

  ## **Final Conclusion & Recommendations**
  - **Salary & Retention**: Employees in lower salary brackets are leaving at a higher rate, indicating that 
    offering better salary increases could help improve retention.
  - **Job Role-Specific Insights**: Sales and technical roles show higher attrition—possible reasons could be work 
    pressure, career growth opportunities, or compensation.
  - **Early Career Turnover**: Employees within the first **0-2 years** in their role are more likely to leave— 
    stronger **onboarding and engagement** strategies may be needed.
  - **Age Group Focus**: Young professionals (**26-35**) show the highest attrition—HR should investigate factors 
    like **career growth, work environment, and compensation**.
  - **Education & Industry Trends**: Life Science and Medical professionals show high attrition, possibly due to 
    **job opportunities elsewhere**. Competitive benefits may help retain them.
