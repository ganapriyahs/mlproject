## Student Performance Analysis

### An End-to-End Machine Learning Project
#### Project Overview
This project analyzes how various demographic and socio-economic factors influence students' academic performance. Using the Students Performance in Exams dataset, we examine the relationship between test scores in Math, Reading, and Writing with features such as Gender, Ethnicity, Parental Education Level, Lunch Type, and Test Preparation Course participation.

The project is divided into two main components:
- Exploratory Data Analysis (EDA): Identifying trends, patterns, and correlations.
- Model Training: Building a predictive model to estimate student scores using the given features.

#### Objectives
- Analyze score distributions across demographic groups.
- Understand the impact of lunch type and test preparation on performance.
- Explore correlations among the three subject scores.
- Develop a machine learning model to predict test scores based on socio-demographic factors.

#### Dataset
Source: Students Performance in Exams – Kaggle
Size: 1,000 rows × 8 columns
Features:
gender – Student’s gender
race/ethnicity – Group classification
parental level of education – Parent/guardian’s highest education
lunch – Standard or free/reduced lunch
test preparation course – Completed or not completed
math score, reading score, writing score – Subject-wise test scores

#### Tools & Libraries
Python – Core programming language
pandas – Data loading and preprocessing
numpy – Numerical operations
matplotlib, seaborn – Data visualization
scikit-learn – Machine learning models and evaluation

#### Key Analysis & Insights
Significant variation in scores based on gender and ethnicity.
Positive correlation between parental education level and student scores.
Students with standard lunch and completed test prep courses performed better.
Strong interdependence between math, reading, and writing scores.

#### Model Training
Conducted in the MODEL TRAINING.ipynb notebook:
Preprocessing: encoding categorical variables, handling missing or skewed data.
Multiple regression models tested for score prediction.
Performance evaluated using metrics like R² (coefficient of determination) and MAE (Mean Absolute Error).

#### Future Work
Implement advanced models (e.g., Random Forest, Gradient Boosting) for improved accuracy.
Conduct statistical hypothesis testing to strengthen conclusions.
Develop an interactive dashboard for exploratory analysis and model deployment.
