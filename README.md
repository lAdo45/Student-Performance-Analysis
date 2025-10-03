# Student-Performance-Analysis

This repository contains a data analysis project built with Python (Pandas, NumPy, Matplotlib, Seaborn) to explore and analyze student performance. The notebook demonstrates how to clean, transform, and visualize educational data to uncover useful insights about students’ marks, performance trends, and patterns.

📘 Project Overview

The goal of this project is to use Python for data-driven insights in education. By applying Pandas operations and visualizations with Seaborn, we answer key questions such as:

Which subjects students perform best in?

What is the average score per student and per subject?

Which students need academic support?

What trends exist in performance across subjects and total marks?

🔎 Questions Solved in This Project

✔️ What is the average score in each subject?

Grouped by subject and calculated mean values.

Visualized with Seaborn barplot for clearer comparison.

✔️ Which student has the highest and lowest total marks?

Used sum(axis=1) across subjects to calculate total score.

Visualized using Seaborn horizontal barplot.

✔️ What percentage of students passed/failed?

Applied conditional filtering (marks ≥ 40 = Pass).

Displayed with a pie chart (Matplotlib).

✔️ What is the overall class performance distribution?

Created bins (Excellent, Good, Average, Poor).

Displayed with a Seaborn histogram / kdeplot.

📊 Charts & Visualizations
1.Impact of Parental Education on Student Performance

Insight: From the visualization, we conclude that higher parental education levels have a positive impact on student scores. Students with parents who completed higher studies generally scored better.

<img width="809" height="575" alt="Relationship between parents education and students score" src="https://github.com/user-attachments/assets/ad767f97-c5ae-4615-bfea-cb2e235193d0" />


2. Impact of Parents’ Marital Status on Student Performance

Insight: From the visualization, we conclude that parents’ marital status has negligible or no significant effect on student scores. Performance trends remain consistent regardless of marital status.
<img width="696" height="549" alt="Impact of marks from parents marital status" src="https://github.com/user-attachments/assets/7aa43ba0-138b-4a03-b7ac-ad78537bd649" />



🛠️ Tools & Libraries Used

Python 3

Pandas → Data cleaning, grouping, and aggregation

NumPy → Numerical operations

Matplotlib → Basic visualizations (pie, bar)

Seaborn → Advanced & stylish visualizations (barplot, countplot, histogram, KDE)

Jupyter Notebook → Step-by-step analysis


🌐 Who Is This For?

Students learning Pandas + Seaborn for Data Analysis

Educators wanting insights into student performance

Beginners practicing real-world data analysis projects
