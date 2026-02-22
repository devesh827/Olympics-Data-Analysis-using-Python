# Olympics-Data-Analysis-using-Python
Olympic Data Analysis (Easy → Advanced)
📌 Project Overview

This project performs an end-to-end exploratory and analytical study of Olympic athlete data using Python.
The objective is to derive real-world insights related to athlete participation, medal distribution, country-wise efficiency, age trends, and performance factors by progressively moving from basic analysis to advanced analytical concepts.

The project is designed to simulate how a data analyst would approach a real, messy dataset and make informed preprocessing and analytical decisions.

🎯 Objectives

Analyze Olympic participation trends across years, countries, and sports

Compare medal-winning vs non-medal performances

Measure country-wise medal efficiency (medals per athlete)

Study age distribution and peak performance ranges

Apply realistic data cleaning strategies for missing values

Create interpretable visualizations for insights

📂 Dataset

Source: Olympic Athlete Events Dataset

File: athlete_events.csv

Description:
Contains athlete-level data including age, gender, height, weight, sport, country (NOC), and medal outcomes for multiple Olympic events.

🧹 Data Cleaning & Preprocessing

Key preprocessing decisions made in this project:

Medal column

Gold, Silver, Bronze grouped as Medal

Non-winning performances treated as No Medal

Binary indicator (medal_Binary) created for analysis

Missing Age values

Handled using context-aware strategies

Automatic age grouping created using pd.cut() for better interpretability

Height & Weight

Missing values handled carefully

Used only where physical analysis was required

Avoided blind row deletion to preserve data integrity

No global row deletion

Missing values treated as structural, not errors

📊 Key Analyses Performed
🔹 Easy Level

Athlete participation over years

Gender distribution

Most popular sports

Medal vs No Medal percentage

🔹 Medium Level

Country-wise athlete participation

Country-wise medal efficiency (medals per athlete)

Sports producing the highest medals

Age distribution of medal winners

🔹 Advanced Level

Automatic age group analysis

Medal trends across age groups

Performance insights using derived features

Efficient aggregation using binary medal indicators

🛠️ Tools & Technologies

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Jupyter Notebook – analysis workflow

📈 Sample Insight

A large majority of Olympic athletes do not win medals, highlighting the high competitiveness of the Games. Certain countries demonstrate higher medal efficiency by winning more medals with fewer athletes, indicating stronger talent development systems.
