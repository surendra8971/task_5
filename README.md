# task_5
📊 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset.
The goal is to analyze passenger information and identify factors that influenced survival.

The dataset contains details such as passenger class, gender, age, fare, and survival status.

🎯 Objective

Understand dataset structure

Handle missing values

Perform data cleaning

Visualize survival patterns

Identify important relationships between features

📁 Dataset Used

File Name: titanic_taks5_raw.csv
The dataset contains passenger details including:

PassengerId

Pclass (Ticket Class)

Name

Sex

Age

SibSp (Siblings/Spouses)

Parch (Parents/Children)

Fare

Embarked

Survived (Target Variable)

🛠 Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

🔎 Steps Performed
1️⃣ Data Loading

Uploaded dataset in Google Colab

Loaded using Pandas

2️⃣ Data Cleaning

Filled missing Age values with median

Filled missing Embarked values with mode

Dropped Cabin column due to many missing values

3️⃣ Data Analysis & Visualization

The following visualizations were created:

Survival Count

Survival by Gender

Survival by Passenger Class

Age Distribution

Correlation Heatmap

📈 Key Insights

Female passengers had a higher survival rate than males.

First-class passengers had better survival chances.

Younger passengers had slightly higher survival probability.

Passenger class and gender strongly influenced survival.

📷 Output

The notebook generates multiple graphs and a correlation matrix to better understand survival patterns.
