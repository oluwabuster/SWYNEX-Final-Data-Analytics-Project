# SWYNEX Final Data Analytics Project  
### Titanic Survival Analysis

## 1. Problem Statement
The goal of this project is to analyze the Titanic passenger dataset to understand the factors that influenced survival during the disaster.  
We aim to answer questions such as:
- Who had a higher chance of survival?
- How did gender, passenger class, and age affect survival?
- What insights can help us understand the tragedy better?

## 2. Dataset Information
- **Dataset Name**: Titanic Dataset
- **Source**: Kaggle
- **Original Records**: 891 passengers
- **Features Used**: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Embarked

## 3. Data Cleaning Process (Task 1)
Problems found in the raw data:
- Age: 177 missing values
- Cabin: 687 missing values
- Embarked: 2 missing values

Cleaning steps performed:
- Filled missing Age values with the median
- Filled missing Embarked values with the mode
- Dropped the Cabin column (too many missing values)
- Removed duplicate rows
- Standardized the Sex column

**Tool used**: Python (Pandas) on Google Colab

## 4. Exploratory Data Analysis (Task 2)
Key Insights:
1. Females had a much higher survival rate (74.2%) compared to males (18.9%).
2. 1st Class passengers had the highest survival rate (63%), while 3rd Class had only 24%.
3. Overall survival rate was 38.4%.
4. Most passengers were between 20–40 years old.
5. Higher ticket fares were associated with better survival chances.

## 5. Interactive Dashboard (Task 3)
Created an interactive dashboard using **Power BI** that includes:
- KPI Cards: Total Passengers, Total Survivors, Survival Rate, Average Age
- Charts: Survival by Gender, Survival by Class, Survival by Embarked, Age Distribution
- Interactive Filters (Slicers): Gender, Passenger Class, Embarked Port

## 6. Key Business Insights
- Gender was the strongest predictor of survival (Women and children first policy).
- Socio-economic status (Passenger Class) significantly affected survival chances.
- Passengers who paid higher fares had better access to lifeboats.
- Young adults formed the majority of the passengers.

## 7. Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- Microsoft Power BI
- GitHub

## 8. Project Structure
- cleaned_titanic.csv
- Titanic_Survival_Dashboard.pbix
- Screenshots of analysis and dashboard
