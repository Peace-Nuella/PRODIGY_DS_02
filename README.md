# PRODIGY_DS_02

### Titanic Dataset EDA Project
#### Overview
This project focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset, which is widely used in data science for demonstrating data analysis techniques. The goal is to explore relationships between variables and identify patterns and trends in the data.

#### Dataset
The Titanic dataset is available on Kaggle and contains information about the passengers on the Titanic, including features such as:

PassengerId: Unique identifier for each passenger
Survived: Survival status (0 = No, 1 = Yes)
Pclass: Ticket class (1st, 2nd, or 3rd)
Name: Name of the passenger
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Ticket fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

##### Objectives
Clean the dataset by handling missing values and erroneous data.
Perform exploratory data analysis to uncover insights about survival rates and factors affecting survival.
Visualize data relationships using appropriate graphs and charts.

#### Data Cleaning Steps

##### Handling Missing Values:

Identify columns with missing values.
Impute missing values for Age using the median age of passengers.
Drop Cabin due to excessive missingness.
Impute Embarked with the most common port (mode).

#### Data Type Conversion:

Convert categorical variables into numeric format using one-hot encoding or label encoding.
Feature Engineering:

Create a new feature FamilySize by combining SibSp and Parch to analyze the impact of family size on survival.
Exploratory Data Analysis

#### Survival Rate Analysis:

Calculate the overall survival rate and compare it across different classes, genders, and age groups.
Relationship Between Features:

Analyze the survival rates based on Pclass, Sex, and Age.
Use visualizations (e.g., bar plots, histograms, and box plots) to illustrate findings.

#### Correlation Analysis:
Create a correlation matrix to identify relationships between numerical features.
Use heatmaps to visualize correlations.

#### Visualization
Distribution of Age: Plot the age distribution of passengers and highlight the survival status.
Survival by Class: Create a bar chart showing the survival rates across different ticket classes.
Survival by Gender: Generate a bar plot comparing survival rates of male and female passengers.
Family Size Impact: Visualize survival rates against family sizes to explore trends.
Conclusions

#### Summarize key findings from the analysis, such as:
Females had a higher survival rate compared to males.
Passengers in the 1st class had a significantly higher survival rate than those in 2nd and 3rd classes.
Age was a significant factor, with younger passengers more likely to survive.

#### Future Work
Implement predictive modeling to build a survival prediction model based on the cleaned dataset.
Explore additional features that could enhance the model's accuracy.

#### Requirements
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
