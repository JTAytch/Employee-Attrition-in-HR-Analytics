# Predicting-Employee-Attrition-in-HR-Analytics
Predicting Employee Attrition in HR Analytics
Eliana Alon | Lauren Furman | Joseph Aytch | Michelle Valencia 

DSC450 Applied Data Science 
Fall 2024 
Domain:

The focus on employee attrition in HR analytics is to evaluate various factors influencing attrition rates to provide a comprehensive understanding of why employees leave and identify areas for improvement in retention strategies.
Job Satisfaction: Employee contentment with their roles, responsibilities, and work-life balance.
Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset 

Career Development: Opportunities for growth and professional development within the company.
Link: https://www.kaggle.com/datasets/tejashvi14/employee-attrition-dataset 

Compensation and Benefits: Role of salary, bonuses, and other financial incentives in retention.
Link: https://www.kaggle.com/datasets/tejashvi14/employee-attrition-dataset 

Work Environment: Organizational culture, team dynamics, and workplace environment.
Link: https://www.kaggle.com/datasets/tejashvi14/employee-attrition-dataset 

Employee Engagement: Levels of employee involvement, motivation, and emotional commitment to their work.
Link: https://www.shrm.org (search “Employee Engagement”)

Demographics: Impact of factors such as age, education level, and gender on attrition rates.
Link: https://books.google.com/ (search “Employee Turnover” by Hom and Griffeth)

Organizational Support: Perceived support from the organization and management.
Link: https://www.academia.edu/ (search “The unfolding model of voluntary employee turnover” by Lee and Mitchell)

Training and Development: Availability of training programs and advancement opportunities.
Link: https://onlinelibrary.wiley.com/ (search “Targeted employee retention” by Hausknecht et al.)

Work-Life Balance: Flexibility in scheduling, remote work options, and overall balance.
Link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9968937/

Overall Satisfaction: General employee satisfaction and likelihood of recommending the organization.
Link: https://www.researchgate.net/ (search “An organization-level analysis of voluntary and involuntary turnover” by Shaw et al.)
Dataset:
The dataset for this project is a publicly available HR dataset that includes various features related to employee demographics, job satisfaction, career progression, and organizational attributes. This data will be used to build predictive models for attrition.
Data Fields:
Age: Employee age.
Education Level: Highest level of education attained.
Department: Department where the employee works.
Job Role: The employee's specific role.
Monthly Income: Employee’s monthly salary.
Years at Company: Tenure at the organization.
Job Satisfaction: Self-reported satisfaction with job.
Work-Life Balance: Employee rating of their work-life balance.
Overtime: Whether the employee works overtime.
Attrition: Indicator of whether the employee has left the organization.

Dataset Location:
The dataset can be accessed at:
 https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction.

Research Questions:

What are the primary factors that predict employee attrition?
How does job satisfaction influence an employee’s decision to stay or leave?
What role do demographic variables (e.g., age, education level) play in attrition rates?
Can machine learning models effectively predict which employees are likely to leave?
How can the results inform HR departments about improving retention strategies?

Benefits:
Enhanced Employee Retention: By identifying key factors that contribute to attrition, organizations can proactively address issues and retain valuable employees.
Targeted Retention Strategies: Insights from the analysis can help HR departments design specific interventions tailored to employee needs.
Informed Decision-Making: Predictive insights enable HR teams to make data-driven decisions regarding employee retention.
Improved Workplace Satisfaction: By understanding factors that affect employee satisfaction, organizations can foster a positive work environment.
Resource Allocation: The analysis helps allocate resources effectively to improve areas that impact employee retention the most. 
Method:
To analyze the dataset effectively, the following methods will be employed:
Data Preprocessing:
Data Cleaning: Handle missing values, remove duplicates, and ensure data consistency.
Data Transformation: Encode categorical variables and standardize numerical values.
Normalization: Normalize data to ensure uniform scaling across features.
Exploratory Data Analysis (EDA):
Descriptive Statistics: Compute mean, median, and other summary statistics for key features.
Visualization: Generate visualizations (e.g., histograms, box plots, scatter plots) to identify trends.
Sentiment Analysis:
Text Processing: Process any text fields (if available) to analyze sentiment.
Sentiment Scoring: Evaluate employee feedback based on sentiment scores.
Keyword Extraction:
Text Mining: Extract frequently mentioned keywords from feedback for thematic analysis.
Statistical Analysis:
Correlation Analysis: Identify correlations between variables (e.g., monthly income and attrition).
Hypothesis Testing: Use hypothesis tests to validate significant findings.
Comparative Analysis:
Group Comparisons: Compare attrition rates among different groups (e.g., by department or role).
Predictive Modeling:
Model Building: Use logistic regression, decision trees, and other algorithms to predict attrition.
Model Evaluation: Assess models using metrics like accuracy, precision, recall, and F1-score.
Clustering:
Segmentation: Use clustering algorithms (e.g., K-means) to categorize employees based on attrition risk.


Potential Issues:

Data Quality:
Missing Data: Incomplete records may impact the quality of analysis.
Inconsistent Data: Variations in data formats can complicate preprocessing.
Bias in Data:
Sampling Bias: Dataset may not represent all employee populations.
Response Bias: Employees with strong opinions may be more likely to provide feedback.
Privacy and Ethical Concerns:
Data Privacy: Ensure compliance with data privacy regulations.
Ethical Use of Data: Handle employee data ethically to avoid any adverse impacts.
Interpretation of Results:
Correlation vs. Causation: Correlations do not imply causation, requiring careful interpretation.
Complex Interactions: Interdependent factors may require sophisticated analysis methods.
Technical Challenges:
Data Integration: Integrating multiple data sources can be challenging.
Scalability: Large datasets require efficient processing resources.
Generalizability:
Context-Specific Findings: Results may be specific to the dataset context and not generalizable to other organizations.
  
Conclusion:

In summary, this project seeks to deliver an in-depth analysis of employee attrition factors within an organization. By exploring factors such as demographics, job satisfaction, and work environment, this project aims to identify critical insights that can inform HR strategies to enhance employee retention. Through techniques like EDA, predictive modeling, and clustering, we aim to provide a comprehensive understanding of the underlying causes of attrition and suggest actionable retention strategies based on data-driven insights.

