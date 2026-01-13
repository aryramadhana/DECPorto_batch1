# DEC Project Learn

<p align="center">
  <img src="assets/logo.png" alt="The Key" width="400" />
</p>

## Project Overview
This project performs a rigorous statistical validation of The Key’s course placement system. By analyzing data from 150 students across three proficiency levels (Advanced, Intermediate, and Foundation), we aim to prove the scientific link between a student's natural aptitude and their eventual academic success.

The primary objective is to ensure that students are placed in learning environments that match their capabilities, thereby optimizing the quality of the English language programs.

## Project Structure
```
.
├── README.md                        # This file
├── assets                           # Complete Jupyter notebook with all calculations/
│   └── logo.jpg                     # company logo         
├── analysis_notebook.ipynb          # analysis report        
├── report in progress.pdf           # analysis report
└── requirements.txt                 # Python dependencies
```

## Data Dictionary
student_id: Unique identifier for each student.

course_level: Categorical data (Foundation, Intermediate, Advanced).

performance_score: Academic GPA on a scale of 0.0 - 4.0.

aptitude_score: Standardized test score on a scale of 0 - 100.

## Research Questions
1. Do students with different performance levels enroll in different course levels?
2. Are there significant differences in aptitude scores across course levels?
3. What is the correlation between aptitude scores and performance?
4. What are the implications for course placement and program quality?

## Potential Use Cases & Future Development
This integrated project serves as a foundation for several Data Science applications:

Predictive Modeling (Regression): Developing a Machine Learning model to predict a student's final GPA based on their initial entry test.

Clustering Analysis: Using unsupervised learning to see if student groupings naturally align with the existing Foundation/Intermediate/Advanced tiers.

Interactive Visualization: Creating dashboards to monitor student progress and identifying "outliers" (e.g., students with low aptitude but high performance) for further pedagogical study.