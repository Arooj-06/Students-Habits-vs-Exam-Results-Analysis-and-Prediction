# Students-Habits-vs-Exam-Results-Analysis-and-Prediction
# Student Habits and Exam Score Analysis

## Project Overview

This project analyzes how different student habits affect exam performance. The dataset contains information about students' daily habits such as study hours, social media usage, Netflix usage, attendance percentage, sleep hours, exercise frequency, mental health rating, diet quality, parental education level, internet quality, part-time job status, extracurricular participation, and exam score.

The main goal of this project is to explore relationships between student lifestyle habits and exam results, then identify which factors are most strongly connected with better academic performance.

## Dataset

The dataset is provided in CSV format and contains 1000 student records.

### Main Columns

- `student_id`
- `age`
- `gender`
- `study_hours_per_day`
- `social_media_hours`
- `netflix_hours`
- `part_time_job`
- `attendance_percentage`
- `sleep_hours`
- `diet_quality`
- `exercise_frequency`
- `parental_education_level`
- `internet_quality`
- `mental_health_rating`
- `extracurricular_participation`
- `exam_score`

## Project Objectives

- Load and understand the dataset
- Check missing/null values
- Clean unrealistic or incorrect values
- Analyze numerical and categorical features
- Find correlation between habits and exam score
- Visualize important trends using graphs and heatmaps
- Identify key factors affecting exam performance
- Give useful recommendations based on analysis

## Tools and Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Main Analysis Performed

### 1. Data Loading

The dataset was loaded using Pandas.

### 2. Data Cleaning

Missing values were checked and handled. Unrealistic values were also reviewed, such as study hours greater than 24 hours per day.

### 3. Exploratory Data Analysis

The project explored:

- Average exam score by gender
- Average exam score by part-time job status
- Average exam score by extracurricular participation
- Relationship between study hours and exam score
- Relationship between screen time and exam score
- Relationship between attendance and exam score
- Correlation between numerical variables

### 4. Key Findings

- Study hours per day showed a strong positive relationship with exam score.
- Excessive Netflix and social media usage showed a negative relationship with exam score.
- Students with better attendance generally had better exam scores.
- Healthy habits such as sleep, exercise, and mental health may support better academic performance.
- Students without part-time jobs performed slightly better on average.
- Extracurricular participation also showed a positive effect on average exam score.

## Recommendations

Based on the analysis:

- Students should increase productive study hours.
- Students should reduce excessive screen time, especially Netflix and social media usage.
- Students should maintain good attendance.
- Students should focus on sleep, exercise, and mental well-being.
- Students should balance extracurricular activities with academic work.

## Future Work

In the future, this project can be improved by adding a machine learning model to predict exam scores based on student habits. Regression models such as Linear Regression, Random Forest Regressor, or Gradient Boosting can be used for prediction.

## Project Files

```text
Student-Habits-Exam-Analysis/
│
├── PROJECT_Arooj_Fatima.ipynb
├── Students_habits.csv
├── README.md
