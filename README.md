# CodeAlpha_Project_Exploratory-Data-Analysis-EDA-

🚢Titanic Dataset- Exploratory data analysis (EDA)
Objective
The task is to perform exploratory analysis on the well-known Titanic dataset. The aim here is to:

Understand the structure and content of the dataset itself.

To clean and prepare the data for analysis.

Identify patterns and trends regarding passenger survivals.

Visualize findings through graphs and plots.

Summarize insights and observations inferred from data.

What to Submit
Python notebook or script titanic_eda.ipynb or eda_process.py

Visualizations embedded throughout the notebook or saved as images in the repository

This summary must clearly explain the dataset, key findings, and interesting observations.

Dataset Overview
The Titanic dataset refers to a data set of passengers aboard the RMS Titanic, which sank on its first voyage in 1912. It contains demographic and survival information for each passenger.

Major Features 
1.Survived: Survival status (0 = No, 1 = Yes) 

2.Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)

3. Name; Sex; Age with

4.SibSp: Number of siblings and/or spouses aboard

Parch: Number of parents/children aboard

Ticket; Fare; Cabin; Embarked

Key Findings from the Analysis
1. Survival Distribution

About 38 percent of the passengers survived.

Survival ratio: Women had much higher survival chances compared to men.

2. Effect of Gender 

Survival rating of female passengers was high (~75%) while most male passengers failed to survive.

This indicates a typical evacuation strategy of "women and children first".

3. Class wise effect of passengers 
1st class passengers had the highest probability of survival.

3rd class passengers had the lowest survival rate.

There was a pronounced class-based difference in their chances of survival.

4. Age Distribution 
Children/young passengers had a comparatively higher survival rate.

Most deaths were in the 20-40 age group, particularly among males.

5. Correlation Insight Weak to moderate

correlation found in analysis between Pclass, Fare, and Survived. 

More than age or alone fare, gender and class were better indicators of survival.

Visualizations Created 
Survivor Count Plot 
Age Distribution by Survival (Histogram with KDE) 
Correlation Heatmap (for numeric features) 
Survival by Class 
Survival by Gender 

Interesting Patterns & Anomalies 
Survival rate was incredibly high among 1st class women. 

Lowest chance of survival among men was in 3rd class saw. 

Although fares are high, it can't be said that all the rich passers survived; complexity can't be confined to wealth alone. 

Missing data in Cabin and Age need some preprocessing. 

Cabin was implemented in dropping columns as there were too many missing values. 

While keeping the feature for analysis, Age was imputed with the median. 

Final Notes 
This EDA helps us understand which features had the most influence on survival and prepares the dataset for possible applications of machine learning models in future endeavors. 

Dataset Source: Kaggle Titanic Dataset

![image](https://github.com/user-attachments/assets/30e43d0b-5ab7-4f46-bca4-c4ac025a7ca7)
![image](https://github.com/user-attachments/assets/63fa3f30-44a6-423e-ae4a-3d357d57c044)

![image](https://github.com/user-attachments/assets/dc625513-0ab3-4937-b23e-cc0758d52acb)
![image](https://github.com/user-attachments/assets/3ccd1f9a-6099-4f5b-8a30-c1f1497ef66a)
![image](https://github.com/user-attachments/assets/23bde74e-0ca0-41ad-b2a4-e23b204e5f7c)
![image](https://github.com/user-attachments/assets/01792f6e-dc0f-4bf9-878d-066a2f68c10d)
![image](https://github.com/user-attachments/assets/d02cd0b2-9193-4e92-a363-1e3eea71428c)






