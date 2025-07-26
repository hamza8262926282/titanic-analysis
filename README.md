# **Titanic Dataset Analysis**

## **Overview**

This project analyzes the Titanic dataset to explore factors influencing passenger survival rates. Using Python and libraries like pandas, numpy, matplotlib, and seaborn, the analysis includes data cleaning, feature engineering, and visualizations to uncover insights about survival patterns.



Prerequisites

Python 3.11
Jupyter Notebook
Required Python libraries (listed in requirements.txt)

**Install Dependencies:**

**pip install -r requirements.txt**




Dataset

The dataset (data/titanic.csv) contains information about Titanic passengers, including:

PassengerId: Unique ID
Survived: Survival status (0 = No, 1 = Yes)
Pclass: Passenger class (1, 2, 3)
Name: Passenger name
Sex: Gender
Age: Age in years
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Ticket fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)


## **The notebook performs the following:**

Data Cleaning: Removes missing values and duplicates.
Feature Engineering: Creates Title, AgeGroup, and FamilySize columns.
Exploratory Data Analysis: Calculates survival rates and visualizes survival by title.



## **Key Findings:**

Overall survival rate: 67.21%

Women had a higher survival rate (93.18%) than men (43.16%).

First-class passengers had a higher survival rate (67.09%).

Children (0-12) had a higher survival rate (81.82%).

Passengers embarking from Cherbourg had the highest survival rate (73.85%).

Titles 'Mrs' and 'Miss' were associated with higher survival rates.

Higher fares correlated with better survival chances.

Medium-sized families (2-4 members) had better survival rates.


## **Visualizations**

The notebook includes a bar plot showing survival rates by passenger title, with percentage labels for clarity.

## **License**

This project is licensed under the MIT License.

## **Acknowledgments**


The Titanic dataset is sourced from public datasets (e.g., Kaggle).

## **Built with pandas, numpy, matplotlib, and seaborn.**
