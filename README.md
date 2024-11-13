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

### How is attrition dependent on Age?

![newplot](https://github.com/user-attachments/assets/536dc8f3-95d8-4cb7-81e8-fd02d1af36ea)

Observation: As seen in the chart above, the attrition is maximum between the age groups 28-32. The attrition rate keeps on falling with increasing age, as people look after stability in their jobs at these point of times. Also at a very younger age, i.e. from 18-20, the chances of an employee leaving the organization is far more- since they are exploring at that point of time. It reaches a break even point at the age of 21

### Is income the main factor towards employee attrition?

![newplot-2](https://github.com/user-attachments/assets/ed407486-e644-4e23-a990-4a21ba4c1b39)

Observation As seen in the above chart, the attrition rate is evidently high at very low income levels- less than 5k monthly. This decreases further- but a minor spike is noticed aorund 10k- indicating the middle class liveliood. They tend to shift towards a better standard of living, and hence move to a different job. When the monthly income is pretty decent, the chances of an employee leaving the organization is low- as seen by the flat line



![newplot-3](https://github.com/user-attachments/assets/ae8497f3-74d4-4f5d-bef2-fa5596e310a6)

![newplot-4](https://github.com/user-attachments/assets/e7935393-6904-4ebe-96ec-d42619a738aa)

![newplot-5](https://github.com/user-attachments/assets/7ea3c8b0-b3c2-46be-8072-c0e054223162)

![newplot-6](https://github.com/user-attachments/assets/29e524b0-8a4d-4b35-88be-53c5e81bc7de)

![newplot-7](https://github.com/user-attachments/assets/f83e44f9-eae0-4543-b206-e3ebcb9cf035)

![newplot-8](https://github.com/user-attachments/assets/040f3477-5853-494e-a11e-a8f1510d4705)

![newplot-9](https://github.com/user-attachments/assets/077a745f-9dff-4a98-a53e-1f97c1928539)

![newplot-10](https://github.com/user-attachments/assets/df56234f-e3d8-4635-bdfd-6a8ab964a1a7)

![newplot-11](https://github.com/user-attachments/assets/8ab4a4b3-1a18-4a13-afd9-ae66ac1f1003)
---

## 🌿 Results and Conclusion
Summary
I have checked the data, and have come to infer the following observations:
- People tend to switch to different jobs at the start of their careers, or at the earlier parts of it. Once they have settled with a family or have found stability in their jobs, they tend to stay long in the same organization- only going for vertical movements in the same organization.
- Salary and stock options have a great motivation on the employees and people tend to leave the organization much less. Higher pay and more stock options have seen more employees remain loyal to their company.
- Work-life balance is a great motivation factor for the employees. However, people with a good work-life balance, tend to switch in search of better opportunities and a better standard of living.
- Departments where target meeting performance is very crucial (e.g. Sales) tend to have a greater chance of leaving the organization as compared to departments with more administrative perspective (E.g. Human Resources)
- People with good Job Satisfaction and environmental satisfaction are loyal to the organization- and this speaks out loud for any Organization. However, people who are not very satisfied with their current project- tend to leave the organization far more.

Through this project, I have strengthened my skills in data preparation and visualization, and the insights derived from this dashboard can guide organizations in shaping more effective retention strategies.

