🚢 Titanic Dataset — Exploratory Data Analysis (EDA)

This repository presents a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset with the primary goal of understanding the data before applying any machine learning models. The analysis focuses on uncovering data distributions, identifying data quality issues, and extracting meaningful real-world insights that influenced passenger survival.

📌 Dataset Information

Source: Seaborn Titanic Dataset
Total Records: 891 passengers
Total Features: 15
Target Variable: survived (0 = Did not survive, 1 = Survived)


🎯 Objectives of the Analysis

1. Examine overall data structure and feature distributions
2. Identify and handle missing values and inconsistencies
3. Detect skewness, variance, and outliers in numerical features
4. Analyze relationships between passenger attributes and survival outcomes
5. Develop intuition and domain understanding prior to modeling


🔍 Dataset Overview

Survival Distribution:
Survived: ~38%
Did not survive: ~62%

The target variable is imbalanced.
The dataset contains both numerical and categorical features.

🧹 Data Quality \& Preprocessing

Feature: Age
Issue: ~20% missing values
Action Taken: Imputed using mean age (~29.7 years)

Feature: Cabin
Issue: Excessive missing values
Action Taken: Dropped from analysis


📊 Numerical Insights

Age:
Mean age: ~29.7 years
Majority of passengers were between 20–40 years
Presence of elderly outliers

Fare:
Median fare: ~14.45
Highly right-skewed distribution
Extreme values up to 512
Identified as a high-variance (risky) feature


🧍 Categorical Insights

Gender Distribution
Male passengers outnumbered females

Passenger Class
Majority of passengers belonged to 3rd class

🔗 Survival Analysis — Key Findings

Survival by Gender
Females: ~74% survival rate
Males: ~19% survival rate

Survival by Passenger Class
1st Class: ~63%
2nd Class: ~47%
3rd Class: ~24%


Overall Observations
1. Higher fare is associated with higher survival probability
2. Higher passenger class leads to better survival outcomes
3. Women and children had a clear survival advantage


📈 Multivariate Observations

Survivors are predominantly clustered at higher fare ranges

Strong relationships observed:
Fare ↑ → Survival ↑
Passenger Class ↑ → Survival ↓

These patterns reflect the socio-economic influence on survival outcomes.


🧠 Key Takeaways

* The dataset is imbalanced
* Fare contains significant outliers and high variance
* Most influential features identified: sex, pclass, fare, age
* Meaningful real-world survival patterns emerge even before modeling

EDA is not about plotting charts — it is about asking the right questions and extracting stories from data.


🛠️ Tools \& Libraries Used

Python
Pandas
NumPy
Seaborn
Matplotlib




