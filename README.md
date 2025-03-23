🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

📚 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic Dataset. The objective is to analyze the dataset to discover insights about the passengers, understand data distributions, and identify patterns that could help predict survival outcomes.

The analysis involves:

Handling missing values.

Visualizing distributions and correlations.

Identifying key factors influencing passenger survival.

Providing actionable insights for model preparation.


🎯 Key Objectives
Load and explore the Titanic Dataset.

Clean and preprocess the data for analysis.

Perform statistical and visual analysis to identify patterns.

Identify correlations between passenger attributes and survival rate.

Summarize key findings and insights for future model building.

📝 Dataset Information
Dataset Name: Titanic.csv

Number of Rows: 891

Number of Columns: 12

Column Description:

PassengerId – Unique identifier for each passenger.

Survived – Survival status (0 = No, 1 = Yes).

Pclass – Ticket class (1st, 2nd, 3rd).

Name – Passenger name.

Sex – Gender of the passenger.

Age – Passenger age.

SibSp – Number of siblings/spouses aboard.

Parch – Number of parents/children aboard.

Ticket – Ticket number.

Fare – Ticket fare.

Cabin – Cabin number.

Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

📊 EDA Process Overview
The EDA process includes the following steps:

1. 🧹 Data Preprocessing
Load the dataset and inspect missing values.

Handle missing data (imputation/removal).

Encode categorical features where necessary.

2. 🔎 Data Exploration
Summarize dataset using descriptive statistics.

Analyze distributions of numerical and categorical features.

Check relationships between survival and passenger characteristics.

3. 📈 Data Visualization
Visualize survival rates by class, gender, and age.

Plot correlations using heatmaps.

Plot bar charts, histograms, and box plots for key insights.

4. 📊 Correlation Analysis
Use heatmaps to observe correlations.

Identify features with the highest influence on survival.

📊 Key Insights and Findings
Survival Rate by Gender:

Females had a significantly higher survival rate than males.

Survival Rate: Female ~ 74%, Male ~ 18%.

Survival Rate by Class:

1st class passengers had the highest survival rate, followed by 2nd and 3rd classes.

Higher ticket class correlates with better survival.

Age Distribution:

Most passengers were between 20-40 years of age.

Children under 10 had a higher survival rate.

Correlation Heatmap:

Pclass, Fare, and Sex have the most correlation with survival.

Fare has a positive correlation with survival.

🛠️ Technologies Used
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔎 Data Preprocessing Steps
Imputed missing values in Age and Embarked.

Dropped columns with too many missing values (Cabin).

One-hot encoding applied for Sex and Embarked.

Standardized numerical features for better analysis.

📢 Future Improvements
Apply feature engineering to improve model predictions.

Build predictive models using Logistic Regression, Random Forest, and SVM.

Deploy a web application using Flask for interactive visualizations.


