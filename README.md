# Bachelor-s-project-on-data-analysis-with-Python
📊 Project Overview
This project analyzes factors influencing student academic probation using machine learning and statistical methods. The analysis identifies key predictors of academic probation and provides actionable insights for educational institutions.

🎯 Objectives
Identify significant factors contributing to academic probation

Build predictive models using logistic regression

Provide data-driven recommendations for student support

Develop early warning systems for at-risk students

📁 Dataset Description
The dataset contains 17 features for each student:

Feature	Description	Type
ID	Student identifier	Numeric
Gender	Student gender	Categorical
Age	Student age	Numeric
Faculty	Academic faculty	Categorical
Previous_GPA	Previous semester GPA (0-20)	Numeric
Credits_Taken	Number of credits taken	Numeric
Study_Hours	Weekly study hours	Numeric
Attendance_Rate	Class attendance percentage	Numeric
Work_Hours	Weekly work hours	Numeric
Commute_Time	Daily commute time (minutes)	Numeric
Financial_Stress	Financial pressure level (1-5)	Numeric
Internet_Quality	Internet quality rating (1-5)	Numeric
Exam_Anxiety	Exam anxiety level (1-5)	Numeric
Sleep_Hours	Average nightly sleep hours	Numeric
Previous_Probation	History of academic probation	Categorical
Current_Probation	Current probation status (target)	Binary
🔧 Technical Implementation
Libraries Used
python
pandas, numpy, matplotlib, seaborn
scikit-learn, statsmodels, scipy
Analysis Steps
Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Exploratory Data Analysis

Descriptive statistics

Correlation analysis

Visualization of key relationships

Predictive Modeling

Logistic regression for classification

Feature importance analysis

Model evaluation metrics

Statistical Analysis

T-tests for group comparisons

Multiple regression analysis

Hypothesis testing

📈 Key Findings
Top Predictors of Academic Probation
Previous Semester GPA (Strongest predictor)

Weekly Study Hours

Class Attendance Rate

Financial Stress Level

Weekly Work Hours

Performance Metrics
Model Accuracy: 85.2%

ROC AUC Score: 0.89

Precision: 0.83

Recall: 0.79

💡 Recommendations
Institutional Interventions
Academic Support Programs for students with GPA < 14

Time Management Workshops to improve study habits

Financial Aid Programs for economically disadvantaged students

Early Warning Systems to identify at-risk students

Mental Health Support for stress and anxiety management

Student-Focused Strategies
Maintain minimum 15 hours weekly study time

Achieve at least 80% class attendance

Balance work hours with academic commitments

Prioritize 7+ hours of nightly sleep

Seek financial counseling when needed

🚀 How to Run
Installation
bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl
Execution
python
# Run the complete analysis
python student_probation_analysis.py
Output Files
probation_analysis_results.json - Complete analysis results

correlation_matrix.png - Visualization of feature correlations

feature_importance.png - Key predictors visualization

roc_curve.png - Model performance evaluation

📊 Results Interpretation
Model Insights
The logistic regression model successfully identifies students at risk of academic probation with 85% accuracy. The most significant factors are previous academic performance (GPA) and study habits, followed by socioeconomic factors like financial stress and work commitments.

Actionable Thresholds
High Risk: GPA < 12.5 + Study Hours < 3.5 weekly

Medium Risk: GPA 12.5-14 + Financial Stress > 3

Low Risk: GPA > 14 + Study Hours > 4 weekly

🔮 Future Work
Potential Enhancements
Incorporate additional data sources (e.g., library usage, online activity)

Implement real-time monitoring system

Develop personalized intervention recommendations

Expand to multi-semester predictive analysis

Add natural language processing for student feedback analysis

Technical Improvements
Experiment with ensemble methods (Random Forest, XGBoost)

Implement deep learning approaches

Develop API for real-time predictions

Create interactive dashboard for administrators

👥 Contributors
Data Analysis: [Your Name]

Model Development: [Your Name]

Documentation: [Your Name]

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Acknowledgments
Educational institutions that provided data

Open-source community for analytical tools

Research in educational data mining and learning analytics

📞 Contact
For questions or collaborations, please contact:

Email: [mohamadbahiraei.com]

GitHub: [MRezada]
