# Data Cleaning and Exploratory Data Analysis

## AI & ML Internship — Week 1

This project was completed as part of the Vortex Tech AI & ML Internship Program 2026.

The objective of this task was to clean a raw student dataset and perform exploratory data analysis using Python, Pandas, Matplotlib, and Seaborn.

## Project Objectives

- Load and inspect a public dataset
- Identify missing values
- Check for duplicate records
- Examine data types
- Clean the dataset
- Generate summary statistics
- Create basic data visualizations
- Identify important patterns and observations

## Dataset

The project uses a student dataset containing demographic and academic performance information.

The dataset includes the following features:

- Student ID
- Name
- Age
- Gender
- Quiz 1 Marks
- Quiz 2 Marks
- Quiz 3 Marks
- Total Assignments
- Assignments Submitted
- Midterm Marks

The dataset contains 300 student records.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The dataset was inspected for missing values, duplicate records, and data types.

The cleaning process included:

- Identifying missing values
- Handling missing values
- Checking and removing duplicate records
- Verifying appropriate data types
- Creating a cleaned dataset for further analysis

## Exploratory Data Analysis

The following analysis was performed:

- Descriptive statistics using `describe()`
- Mean and median calculations for academic marks
- Frequency counts using `value_counts()`
- Analysis of quiz performance
- Analysis of gender distribution
- Visualization of the relationship between Quiz 1 marks and Midterm marks

## Visualizations

The notebook contains the following visualizations:

1. Histogram of Quiz 1 Marks
2. Bar Chart of Gender Distribution
3. Scatter Plot of Quiz 1 Marks vs Midterm Marks

## Key Findings

The exploratory analysis provides an overview of students' academic performance and demographic distribution.

The visualizations help understand the distribution of Quiz 1 marks, the gender distribution of students, and the relationship between Quiz 1 marks and Midterm marks.

The analysis demonstrates how data visualization and descriptive statistics can be used to identify basic patterns in a dataset.

## How to Run

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas matplotlib seaborn jupyter

week 1
│
├── data_cleaning.ipynb
├── student_dropout_behavior_dataset-selected-columns.csv
└── README.md
