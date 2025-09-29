# Elevate Labs: Task 5 (Exploratory Data Analysis)
# Dataset - Titanic

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset, a classic dataset from Kaggle.  
The goal is to explore passenger demographics, socio-economic factors, and survival outcomes using **Python, Pandas, Matplotlib, and Seaborn**.

## Objectives
- Explore and understand dataset structure.
- Perform statistical analysis using `.info()`, `.describe()`, `.value_counts()`.
- Visualize distributions and relationships between features.
- Identify key factors influencing passenger survival.
- Summarize insights in a clear report.

## Tools & Libraries
- **Python 3.9**
- **Pandas** → Data manipulation & statistics
- **Matplotlib** → Basic plots
- **Seaborn** → Advanced visualizations

## Dataset Files
- `train.csv` → Training dataset with target (`Survived`)
- `test.csv` → Test dataset (used for predictions/submission)
- `gender_submission.csv` → Sample submission file

### Dataset Columns
- **PassengerId** → Unique identifier
- **Survived** → Survival (0 = No, 1 = Yes)
- **Pclass** → Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name** → Passenger name
- **Sex** → Gender
- **Age** → Age in years
- **SibSp** → # of siblings/spouses aboard
- **Parch** → # of parents/children aboard
- **Ticket** → Ticket number
- **Fare** → Passenger fare
- **Cabin** → Cabin number
- **Embarked** → Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## EDA Workflow
1. **Data Exploration**
   - `.info()`, `.describe()`, `.value_counts()`
   - Check missing values and distributions

2. **Univariate Analysis**
   - Countplots of `Survived`, `Pclass`, `Sex`
   - Histogram of `Age`

3. **Bivariate Analysis**
   - Survival rate vs Class, Gender, Age
   - Boxplots of Age by Survival
   - Scatterplots of Age vs Fare

4. **Multivariate Analysis**
   - Pairplot for numeric features with Survival
   - Correlation Heatmap

5. **Insights & Findings**
   - Females survived more than males
   - 1st class had highest survival rate
   - Younger passengers survived more
   - Higher fares linked to survival
   - Small family groups had better survival chances

## Visualizations
- Countplots
- Histograms
- Boxplots
- Scatterplots
- Pairplot
- Heatmap

## Deliverables
- **Google Colab** → Code & plots
- **PDF Report** → Observations & findings
