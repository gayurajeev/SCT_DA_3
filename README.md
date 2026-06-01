IBM HR Analytics — Employee Attrition Dashboard
Problem Statement:
Employee attrition is a major challenge for organizations, leading to increased recruitment costs, loss of productivity, and reduced organizational efficiency.

The objective of this project is to analyze employee data from IBM HR Analytics to understand:
1.Why employees are leaving the company
2.Which departments and roles have the highest attrition
3.What factors (overtime, income, job satisfaction, etc.) influence attrition
4.How HR teams can identify high-risk employees and improve retention

Project Objective:
To build an interactive HR analytics dashboard that helps stakeholders:

Track overall attrition trends
Identify key drivers of employee turnover
Analyze attrition across departments, roles, and demographics
Support data-driven HR decision-making

Tools & Technologies Used:
Python (Google Colab)
Pandas
NumPy
Matplotlib
Seaborn
Tableau Public
Interactive dashboards
Data visualization
Filters and actions
GitHub
Version control
Project documentation

Dataset:
The dataset used is the IBM HR Analytics Employee Attrition dataset containing employee-level attributes such as:

Age
Department
Job Role
Monthly Income
Job Satisfaction
OverTime
Years at Company
Attrition (Target Variable)

Methodology:
1. Data Collection
Imported IBM HR Attrition dataset into Google Colab
2. Data Cleaning & Preparation (Python)
Checked missing values and data types
Created derived columns:
Attrition Flag (Yes = 1, No = 0)
Age Group
Prepared dataset for visualization in Tableau
3. Exploratory Data Analysis (EDA)
Attrition distribution analysis
Department-wise attrition comparison
Job role-based attrition patterns
Impact of overtime, income, and satisfaction
4. Data Visualization (Tableau)
Built interactive dashboards with filters
Created KPI metrics and comparative charts
Designed HR-focused analytical views
5. Dashboard Publishing
Published on Tableau Public for interactive access

Dashboard Overview:
The Tableau dashboard includes:

🔹 KPI Section
Total Employees
Attrition Count
Attrition Rate
Average Monthly Income
Average Tenure
🔹 Attrition Analysis
Department-wise Attrition
Job Role-wise Attrition
Age Group Analysis
🔹 Key Drivers of Attrition
OverTime vs Attrition
Job Satisfaction vs Attrition
Income vs Attrition
Years at Company vs Attrition
🔹 Risk Segmentation (Behavioral Insights)
High vs Medium vs Low attrition behavior segments (based on patterns observed in data)

Key Insights:
Employees working overtime show significantly higher attrition rates
Certain job roles (e.g., Sales and Laboratory roles) have higher turnover
Lower income employees are more likely to leave the organization
Employees with lower job satisfaction have higher attrition probability
Early-career employees tend to leave the company more frequently

Business Recommendations:
Based on the analysis, the following actions are recommended:

Reduce excessive overtime workload for employees
Improve compensation structure for low-income groups
Implement retention strategies for high-risk job roles
Conduct regular employee satisfaction surveys
Focus on early-career employee engagement programs

Results & Impact:
This project demonstrates how HR analytics can help organizations:

Identify hidden patterns in employee behavior
Predict potential attrition risks
Improve retention strategies
Reduce hiring and training costs
Support data-driven HR decision-making

Tableau Dashboard:
View Interactive Dashboard:
https://public.tableau.com/views/IBMHRANALYTICS_17803311410940/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
