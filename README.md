# 📊 IBM HR Analytics Employee Attrition & Performance Visualization Project

---

## 💡 Project Overview
In this project, I used the **IBM HR Analytics Employee Attrition & Performance** dataset from Kaggle to explore and visualize patterns in employee data, focusing on attrition, performance, and workplace dynamics. The dataset contains information about employees across various attributes, and my objective was to clean, transform, and prepare the data for insightful visualizations in Tableau, enabling stakeholders to better understand factors related to employee engagement and attrition.

---

## ☝️ Project Goals
The main objectives of this project are:
1. **Data Cleaning and Transformation**: Ensure the dataset is free of inconsistencies and is structured for effective visualization.
2. **Exploratory Data Analysis (EDA)**: Identify key trends and patterns in employee demographics, job satisfaction, performance, and attrition.
3. **Tableau Visualization**: Create an interactive dashboard in Tableau that presents insights and enables stakeholders to explore the data intuitively.
4. **Interpretation**: Provide actionable insights from the visualizations to aid in strategic HR planning.

---

## 💼 Tasks
1. **Data Cleaning**: Handle missing values, outliers, and anomalies to create a consistent dataset.
2. **Data Transformation**: Prepare the data for visualization, which includes encoding, aggregating, and reshaping as necessary.
3. **Exploratory Data Analysis (EDA)**: Identify relationships between attributes such as job satisfaction, department, and overtime status.
4. **Tableau Visualization**: Design and develop interactive dashboards to visualize trends and provide insights for HR decision-making.

---

## 🛠️ Tools and Technologies
- **Python**: for initial data cleaning and transformation.
- **Pandas**: for data manipulation.
- **Tableau**: for creating interactive visualizations and dashboards.
- **Jupyter Notebook**: for documenting the data preparation steps and EDA.

---

## 🗂️ Data Sources
The dataset used for this project is:
- **IBM HR Analytics Employee Attrition & Performance** from Kaggle, which includes 35 columns capturing various aspects of employee demographics, performance, and satisfaction.

[Kaggle Dataset Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

### Key Columns:
- **Age**: Employee age in years.
- **Attrition**: Whether the employee has left (Yes/No).
- **BusinessTravel**: Frequency of travel (Rarely, Frequently, etc.).
- **Department**: The department in which the employee works.
- **DistanceFromHome**: Distance from the employee's home to the office (in km).
- **EducationField**: The field of education.
- **JobRole**: The specific role of the employee.
- **JobSatisfaction**: Satisfaction score from 1-4.
- **MonthlyIncome**: Monthly income of the employee.
- **OverTime**: Whether the employee works overtime (Yes/No).
- **PerformanceRating**: Performance rating (1-4).
- **YearsAtCompany**: Total years the employee has worked at the company.

---

## 💻 Process and Steps

### 1️⃣ Step 1: Data Collection
   - Load the dataset from Kaggle and inspect for any data quality issues.

### 2️⃣ Step 2: Data Cleaning
   - Handle missing values and ensure data consistency.
   - Standardize categorical variables and remove any unnecessary columns.
   - Detect and address outliers in numerical columns like `MonthlyIncome` and `YearsAtCompany` that could skew visual insights.

### 3️⃣ Step 3: Data Transformation
   - Encode categorical variables (like `BusinessTravel`, `JobRole`, `EducationField`) to prepare for visualization.
   - Aggregate data where necessary to provide summary insights, such as average attrition rate by department or job role.

### 4️⃣ Step 4: Exploratory Data Analysis (EDA)
   - Examine initial distributions of variables and correlations.
   - Identify key trends, such as how `JobSatisfaction` or `OverTime` correlates with attrition.

### 5️⃣ Step 5: Tableau Dashboard Creation
   - Import the cleaned and transformed data into Tableau.
   - Design interactive charts and graphs:
     - **Attrition by Department**: A breakdown of attrition rates by each department.
     - **Job Satisfaction Distribution**: Show satisfaction levels across departments and roles.
     - **Income and Attrition**: Visualize the correlation between `MonthlyIncome` and attrition.
     - **OverTime Analysis**: Display attrition rates for employees who frequently work overtime.
     - **Years at Company**: Trends in employee retention related to tenure.
   - Create filters and interactive elements to allow users to explore insights dynamically.

### 6️⃣ Step 6: Insights and Reporting
   - Summarize key findings and patterns observed in Tableau.
   - Provide insights on potential actions, like improving job satisfaction or managing overtime, which could help reduce attrition.

## 🖥 Dashboard Link

You can explore the full interactive dashboard on Tableau Public here:  
[HR Analytics Dashboard on Tableau](https://public.tableau.com/views/HRAnalyticsDashboard_17315971551840/HRAnalyticsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="903" alt="Знімок екрана 2024-11-14 о 19 03 39" src="https://github.com/user-attachments/assets/f0dcb392-3908-40cf-9cc5-71905a2e4114">


## 📊 Dashboard Overview

The **HR Analytics Dashboard** showcases various HR metrics and KPIs that provide insights into employee retention, demographics, and job satisfaction. Here’s a quick overview of the metrics covered:

- **Attrition Rate:** Displays the percentage of employees who have left the company, helping to monitor workforce stability.
- **Employee Demographics:** Shows the distribution of employees by age, gender, department, education, and job level.
- **Job Satisfaction & Attrition by Category:** Highlights job satisfaction ratings across departments and job roles to pinpoint areas for improvement.
- **Average Salary & Tenure:** Provides a look into the average income and years of service, indicating financial and experiential employee status.

## 📈 Key Insights

Here are some insights derived from the dashboard:

- **High Attrition in Certain Departments:** Departments like Sales and Human Resources show higher attrition rates, signaling a potential need for employee retention strategies.
- **Attrition by Tenure:** There is a noticeable spike in attrition among employees within the first 1-2 years at the company, suggesting the importance of early employee engagement and support.
- **Salary Influence on Attrition:** Employees in lower salary ranges show higher attrition rates, which might indicate that compensation is a factor in employee turnover.
- **Gender-Based Attrition Trends:** Attrition rates differ by gender across various age groups and job levels, providing a deeper understanding of demographic trends within the workforce.

## 🚀 Project Goals

As a recruiter, I’m working on my data analysis skills to:

- **Leverage Data-Driven Decision Making:** Use data to guide strategic decisions and improve retention and satisfaction in HR.
- **Enhance Recruiting Strategies:** Identify trends and factors impacting employee retention to improve recruitment and talent management.
- **Gain Practical Analytics Experience:** Develop hands-on experience with data tools like Tableau, SQL, and Python to further my data analytics journey.

---

Feel free to explore the dashboard, and reach out with any feedback or questions! 😊
___
