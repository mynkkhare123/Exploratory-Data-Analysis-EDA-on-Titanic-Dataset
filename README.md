# Exploratory-Data-Analysis-EDA-on-Titanic-Dataset
Titanic Survival Analysis - Exploratory Data Analysis (EDA)
Titanic Visualization

# Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic dataset, examining factors that influenced passenger survival rates during the tragic 1912 sinking. The analysis includes data cleaning, transformation, visualization, and statistical insights to understand survival patterns.

# Dataset
The Titanic dataset contains information about 891 passengers including:

Survival status (0 = No, 1 = Yes)

Passenger class (1st, 2nd, 3rd)

Name, Gender, Age

Family relations (Siblings/Spouses, Parents/Children)

Ticket and Fare information

Cabin and Embarkation port

# Analysis Steps
Data Loading & Cleaning

Handled missing values in Age, Cabin, and Embarked columns

Removed irrelevant columns (PassengerId, Ticket, Cabin)

# Statistical Analysis

Calculated survival rates by gender, passenger class, and their combinations

Analyzed age distribution and its relationship to survival

Examined correlation between different variables

# Visualizations

Age distribution histogram

Survival rates by class and gender

Correlation heatmap between numerical features

# Key Findings
Gender Survival Disparity

Female survival rate: 74%

Male survival rate: 19%

Class Impact

1st Class: 63% survival

2nd Class: 47% survival

3rd Class: 24% survival

Combined Factors

1st class females: 97% survival

3rd class males: 13% survival

Age Patterns

Children (<10 years) had 59% survival rate

Most passengers were 20-40 years old



Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Files
titanic_eda.ipynb: Jupyter notebook with complete analysis

titanic_eda_assignment.csv: Dataset file


# Insights Summary
The analysis reveals a stark "women and children first" policy was enforced, with strong socioeconomic bias in survival outcomes. First-class passengers had priority access to lifeboats, while third-class males had less than 15% survival chance. These findings reflect both the emergency protocols and social hierarchies of the era.
