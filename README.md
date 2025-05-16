# HR Analytics - Predict Employee Attrition
This project aims to analyze and predict employee attrition using HR data.
The goal is to help organizations identify the key factors contributing to employee resignation and take proactive measures to retain valuable talent.

# Dashboard Preview
 Project Structure
──> hr_cleaned_data.xls           # Cleaned dataset used for analysis and modeling
──> Screenshot 2025-05-16.png     # Power BI dashboard snapshot
──> attrition_model.ipynb         # Python notebook for model building and SHAP analysis
──> attrition_dashboard.pbix      # Power BI dashboard file
──> README.md                     # Project overview and details
# Objective
Understand the root causes of employee attrition through exploratory data analysis.
Predict future attrition using classification models.
Visualize findings in an interactive Power BI dashboard.
Interpret model results using SHAP (SHapley Additive exPlanations) values.

# Tools & Technologies
Python: Pandas, Seaborn, Scikit-learn, SHAP
Power BI: Dashboard visualization
ML Models: Logistic Regression, Decision Tree

# Key Insights
Attrition Rate: 16.12%
Departments with Highest Attrition: Human Resources & Sales
Age Group Most Affected: 26–35 years
Education Field Impact: Highest attrition in Human Resources and Technical Degree holders
Job Role Insights: Sales Executives showed lower satisfaction levels

# Machine Learning
Model Used: Random Forest (with comparison to Logistic Regression & Decision Tree)
Evaluation: Accuracy, Confusion Matrix
Interpretation: SHAP values for feature importance and explanation of predictions

# Power BI Dashboard
Attrition rates by:
Department
Age Group
Gender
Education Field
Job Satisfaction
Interactive slicers and filters included

# Deliverables
Cleaned HR dataset (hr_cleaned_data.xls)
Python Notebook for modeling and SHAP analysis
Power BI Dashboard (.pbix and screenshot)
Model performance report (Accuracy & Confusion Matrix)
PDF with suggestions to reduce attrition 

# Suggestions for Attrition Prevention
Prioritize employee engagement in high-attrition departments (e.g., HR, Sales)
Implement mentorship programs for younger employees (especially 26–35 age group)
Monitor satisfaction scores regularly for proactive interventions
Re-evaluate compensation and career development opportunities in high-risk roles
