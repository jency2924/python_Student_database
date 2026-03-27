  📊 Student Performance Analysis System (Synthetic Data)

🧾 Project Overview

  Educational institutions generate large volumes of student performance data. Manually analyzing this data is time-consuming and error-prone.
         This project provides an automated system to generate, process, and analyze synthetic 
student data using Exploratory Data Analysis (EDA).
The system helps identify:
Performance trends
Top-performing students
Students needing improvement

🎯 Objectives

This project aims to:
Generate a synthetic dataset of 250 students simulating real-world academic data
Perform data cleaning and preprocessing
Apply descriptive statistics to understand data distribution
Analyze student performance metrics (Total, Average, Grades)
Identify top performers and low performers

Conduct group-based analysis:

Department-wise performance
Gender-wise comparison
Year-wise trends
Study relationships between variables:
Attendance vs Marks
Internal Marks vs Performance

Visualize data using:

Bar Charts
Pie Charts
Histograms
Scatter Plots
Derive meaningful insights for academic improvement
📁 Dataset Description

The dataset consists of 250 student records with the following columns:

Column Name
Description
Student_ID
Unique student ID
Name
Student Name
Gender
Male / Female
Department
CSE / IT / ECE
Year
1st / 2nd / 3rd
Maths
Marks (0–100)
Science
Marks (0–100)
English
Marks (0–100)
Attendance
Percentage (50–100)
Internal Marks
Marks (0–25)

⚙️ Technologies Used
Python

Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Faker – Synthetic data generation

🔄 Project Workflow

Data Generation
Create synthetic student data using Faker and random functions
Data Preprocessing
Handle missing values
Check data types
Ensure consistency
Feature Engineering

Calculate:

Total Marks
Average Marks
Grades
Exploratory Data Analysis (EDA)
Statistical summaries (mean, median, std)
Distribution analysis
Performance Analysis
Identify top performers
Identify failing students
Group-Based Analysis
Department-wise
Gender-wise
Year-wise

Relationship Analysis

Attendance vs Marks
Internal Marks vs Total Marks

Visualization

Bar Charts
Pie Charts
Histograms
Scatter Plots

📈 Key Insights (Example)

Students with higher attendance tend to score better
Internal marks strongly influence total performance
Certain departments may perform better overall
Performance may vary across years and gender

🚀 How to Run the Project

Install required libraries:
Bash

pip install pandas numpy matplotlib seaborn faker

Run the Python script:

Bash

python main.py

View outputs:

Data tables
1.bar chart

<img width="651" height="522" alt="image" src="https://github.com/user-attachments/assets/06934fc3-da9a-4962-b0de-df2d9dafc45a" />


Graphs and visualizations
