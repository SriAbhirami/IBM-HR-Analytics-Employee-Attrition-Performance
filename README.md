IBM HR Analytics: Employee Attrition & Performance
📌 Introduction
Employee attrition is a significant issue in organizations, impacting productivity, morale, and operational costs. This project analyzes HR data to identify patterns and key drivers behind employee turnover using data analysis and machine learning techniques. The objective is to build predictive models that can anticipate attrition and suggest actionable strategies for better employee retention.

🎯 Objectives
📊 Analyze Attrition Rates: Understand attrition patterns across demographics and departments.

🔍 Identify Key Drivers: Determine factors such as job satisfaction, overtime, income, and work-life balance influencing attrition.

🤖 Build Predictive Models: Develop models to identify employees at risk of leaving.

💡 Gain Actionable Insights: Provide recommendations for improving employee engagement and retention.

📂 Dataset Overview
The project uses the IBM HR Analytics Employee Attrition & Performance dataset, which is a fictional dataset created by IBM.

Total Records: 1,470 employees

Features: 35 columns including demographics, job role, satisfaction scores, and performance metrics

Target Variable: Attrition (Yes/No)

🧹 Data Cleaning
✅ Removed constant or irrelevant columns (EmployeeCount, Over18, StandardHours, EmployeeNumber)

✅ Verified data types and checked for missing or duplicate entries

✅ Converted categorical target (Attrition) into binary format (Yes → 1, No → 0)

📊 Exploratory Data Analysis (EDA)
Overall Attrition Rate: 16.12%

Key visual comparisons:

Attrition vs. Overtime

Attrition vs. Monthly Income

Attrition vs. Job Satisfaction

Attrition vs. Distance From Home

⚙️ Feature Engineering
Encoded categorical variables using Label Encoding and One-Hot Encoding

Dropped non-informative columns

Applied Feature Scaling where necessary (e.g., for KNN, Logistic Regression)

🤖 Model Building
Three models were implemented:

Random Forest Classifier

Logistic Regression

K-Nearest Neighbors (KNN)

Dataset split: 70% Training / 30% Testing

Evaluated using Accuracy, Precision, Recall, and F1-Score

📈 Evaluation & Results
Model	Accuracy	Precision	Recall	F1-Score
Random Forest	100%	High	High	High
Logistic Regression	Good	Balanced	Balanced	Good
KNN	Low	Poor	Poor	Poor

⚠️ Note: The 100% accuracy from the Random Forest suggests possible overfitting — recommend cross-validation.

🔍 Key Insights
OverTime is a strong indicator of attrition.

Employees with lower income and job satisfaction are more likely to leave.

Younger employees and specific job roles had higher attrition rates.

Random Forest model performed best, though needs validation.

✅ Conclusion
This project demonstrates how machine learning can enhance HR decision-making. By identifying and understanding the causes of employee attrition, companies can implement better retention strategies and foster a healthier work environment.

📌 Future Scope: Incorporate more complex models, perform cross-validation, and test on real-world datasets for deeper insights.

🛠️ Tools & Technologies
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

IBM HR Analytics Dataset

👩‍💻 Author
Sri Abhirami J.L
