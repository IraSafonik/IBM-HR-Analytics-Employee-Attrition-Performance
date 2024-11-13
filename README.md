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

---

## 🌿 Results and Conclusion
The Tableau dashboard provides a comprehensive view of employee attrition and related factors, helping HR teams to make data-driven decisions. Some of the notable insights include:
- **High attrition in certain departments** and job roles, indicating areas that may benefit from targeted retention efforts.
- **Positive correlation between job satisfaction and retention**, emphasizing the importance of employee engagement.
- **Impact of overtime on attrition**, suggesting that work-life balance could be a factor in employee retention.

Through this project, I have strengthened my skills in data preparation and visualization, and the insights derived from this dashboard can guide organizations in shaping more effective retention strategies.

