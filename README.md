# task-2

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of the AI & ML Internship Task 2. 
The goal is to perform A data analysis on the Titanic dataset to uncover insights, visualize patterns, and prepare the data.

## Objective

To analyze the Titanic dataset using various statistical and visualization techniques in order to:

- Understand the structure and distribution of data
- Handle missing values
- Detect trends, outliers, and correlations
- Derive initial observations for machine learning models
  
## 🛠️ Tools & Libraries Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

Dataset used: `Titanic-Dataset (2).csv`

It includes information such as:
- Passenger class
- Name
- Sex
- Age
- Fare
- Embarked location
- Survival status

##  Steps Performed

1. **Data Loading & Inspection**
   - Viewed first few rows
   - Checked data types and missing values
   - Basic statistical summary

2. **Data Cleaning**
   - Filled missing `Age` with median
   - Filled missing `Embarked` with mode
   - Dropped `Cabin` 

3. **Visualization**
   - Histograms for numerical data
   - Boxplots for outlier detection (`Age`, `Fare`)
   - Countplot for categorical distribution (`Sex`, `Survived`)
   - Heatmap for correlation analysis
   - Pairplot for feature relationships

4. **Analysis**
   - Females had higher survival rate
   - 1st class passengers were more likely to survive
   - Younger passengers had better survival chances
   - Some features are correlated (e.g. Fare and Pclass)
     
## Key Insights

- Gender and passenger class are strong indicators of survival.
- Data had missing values in `Age`, `Embarked`, and `Cabin`.
- Correlation heatmap helped identify related features.
- Visuals provided better understanding of distributions.
