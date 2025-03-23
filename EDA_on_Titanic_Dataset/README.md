# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project explores the **Titanic dataset** to analyze survival trends based on different passenger characteristics. The goal is to clean the dataset, perform univariate and bivariate analysis, and visualize patterns that influenced survival rates.

## Objectives
- Load and clean the dataset
- Handle missing values and data inconsistencies
- Perform **Exploratory Data Analysis (EDA)**
- Identify key factors affecting survival
- Provide insights and recommendations

## Dataset Description
The dataset consists of **1,309 records** and contains information about passengers such as:
- **Survival (0 = No, 1 = Yes)**
- **Passenger class (1st, 2nd, 3rd)**
- **Name, Sex, Age**
- **Family relations (Siblings/Spouses, Parents/Children)**
- **Ticket details, Fare, Cabin, and Embarkation point**

## Data Cleaning
- Dropped columns with excessive missing values (**Cabin, Boat, Body, Home Destination**)
- Filled missing values in **Age** and **Fare** with the median
- Imputed missing values in **Embarked** with the mode
- Rounded **Fare** values for consistency

## Exploratory Data Analysis (EDA)
### **Univariate Analysis:**
- **Most passengers traveled in 3rd class** due to affordability
- **Majority of passengers were aged 15-40**
- **Most passengers traveled alone or with only one family member**
- **Fare distribution was highly skewed**, with a few passengers paying significantly higher fares

### **Bivariate Analysis:**
- **1st class passengers had the highest survival rate**, while **3rd class had the lowest**
- **Female passengers had a much higher survival rate** than males (Aligns with "Women and Children First" policy)
- **Passengers from Cherbourg had a better survival rate**, likely due to a higher proportion of 1st class passengers
- **Passengers with higher fares had a greater chance of survival**
- **Solo travelers had lower survival rates**, while small family groups had better chances

## Key Insights
- **Class & Survival Disparity:** Wealthier passengers had better survival odds.
- **Gender Disparity:** Female survival rate was significantly higher.
- **Embarkation Port Impact:** Cherbourg passengers had the highest survival rate.
- **Family Influence:** Traveling in a small group increased survival odds.
- **Fare & Survival:** Higher-paying passengers had better access to safety resources.

## Recommendations
### **For Future Passenger Safety on Ships:**
- Ensure **equal access to lifeboats** for all passengers, regardless of class.
- Conduct **mandatory lifeboat training** for all passengers.
- Develop **special evacuation protocols** for large families.

### **For the Travel & Cruise Industry:**
- Safety procedures should be **class-independent**.
- Provide dedicated **assistance for elderly and solo travelers**.
- Implement **better crowd management** for efficient evacuations.

### **For Further Historical Research:**
- Analyze the **role of crew members in survival rates**.
- Study **cabin location and its impact on survival chances**.
- Investigate **the influence of social status on survival odds**.

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Missingno)
- **Data Cleaning & Preprocessing**
- **Statistical & Exploratory Data Analysis (EDA)**
- **Data Visualization**

---
### **Conclusion**
This project provided valuable insights into **factors influencing survival rates on the Titanic**. The findings can help **optimize modern safety protocols** and highlight **historical social disparities** in survival chances.

---
**Author:** Danish Karim  
**Date:** March 2025
