# 🎓 Student Performance Prediction

Overview
This project predicts students’ academic performance based on various factors such as study habits, parental education, test preparation, and lunch type.  
The goal is to help educators identify patterns influencing learning outcomes and improve academic results using machine learning.

Objectives
- Perform data preprocessing and exploratory data analysis (EDA)
- Build and compare Linear Regression, Decision Tree, and Random Forest models
- Identify the most influential factors affecting student grades

Tools & Technologies
Programming - Python
Libraries - Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib
IDE - Jupyter Notebook (Anaconda)
 Version Control - Git & GitHub 

Workflow
1. Data Collection 
   Dataset downloaded from [Kaggle: Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

2. Data Preprocessing 
   - Handled missing values  
   - Encoded categorical variables  
   - Created derived features such as `average_score` (mean of Math, Reading, and Writing scores)

3. Exploratory Data Analysis (EDA)  
   - Visualized distributions of scores  
   - Studied correlations between features and target  
   - Identified patterns based on gender, parental education, and test preparation

4. Model Building & Evaluation 
   - Implemented:
     - Linear Regression  
     - Decision Tree Regressor  
     - Random Forest Regressor  
   - Evaluated models using MAE, RMSE, and R² metrics  
   - Selected Random Forest as the best-performing model

5. Model Saving  
   - Saved the trained model using Joblib as `best_rf_model.pkl`

Results
- Best Model: Random Forest Regressor  
- Performance Metric: High R² accuracy on test data  
  Insights: 
  - Students who completed test preparation scored significantly higher  
  - Parental education level positively influenced average performance  
  - Lunch type and study habits correlated with academic success  
