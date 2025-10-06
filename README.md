# Sleep Health and Lifestyle Analysis
Overview

This project analyzes the Sleep Health and Lifestyle Dataset, aiming to understand the patterns in sleep duration, sleep quality, physical activity, stress levels, and related health factors. The dataset contains demographic information along with sleep habits and lifestyle metrics of individuals.

The analysis includes data cleaning, outlier handling, statistical analysis, and visualization to derive meaningful insights.

# Dataset Features

The dataset contains the following key columns:

Feature	Description
Person ID	Unique identifier for each participant
Gender	Gender of the participant (Male/Female)
Age	Age of the participant
Occupation	Participant’s occupation
Sleep Duration	Average sleep hours per day
Quality of Sleep	Self-reported sleep quality (1–10)
Physical Activity Level	Average physical activity level (minutes/day)
Stress Level	Self-reported stress level (1–10)
BMI Category	Body Mass Index category (Normal/Overweight/Obese)
Blood Pressure	Systolic/Diastolic blood pressure reading
Heart Rate	Average heart rate (bpm)
Daily Steps	Number of steps taken per day
Sleep Disorder	Type of sleep disorder, if any
# Data Cleaning & Preprocessing

Remove duplicates: Ensured no repeated records.

Handle missing values:

Numerical columns → filled with median

Categorical columns → filled with mode

Outlier removal: Used Z-score method to remove extreme values beyond 3 standard deviations.

Normalization: Applied log transformation for skewed numeric columns.

Exploratory Data Analysis (EDA)

Distribution plots: Visualized sleep duration, stress levels, and physical activity.

Boxplots: Compared sleep duration across occupations.

# Gender-based analysis:

Compared average sleep duration between males and females.

Conducted T-test to check for statistically significant differences.

Sleep disorder analysis: Pie chart showing distribution of sleep disorders grouped by gender.

# Statistical Analysis

Skewness checked for all numeric columns to ensure normality.

T-test example:

Null hypothesis (H0): No difference in sleep duration between genders

Result: Significant difference found (p-value < 0.05)

# Key Insights

Average sleep duration and quality differ across occupations and genders.

Higher stress levels often correspond to lower sleep quality.

Outliers in metrics like daily steps and heart rate can distort overall analysis, hence removed.

Skewed numeric columns normalized for better statistical analysis.

Visualization Examples

Sleep Duration by Occupation: Bar plot/boxplot

Average Sleep Duration, Stress, and Quality: Histogram or line plots

Gender-based Sleep Duration: T-test visualized via boxplot

Sleep Disorder Distribution by Gender: Pie chart

# Tools & Libraries

Python Libraries: pandas, numpy, matplotlib, seaborn, scipy

Environment: Jupyter Notebook / Google Colab
