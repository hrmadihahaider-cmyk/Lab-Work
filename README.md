# 📊 Student Performance Data Analysis

## 📌 Project Overview

This project focuses on exploratory data analysis (EDA) of a student grading dataset. The objective is to understand the dataset structure, clean the data, analyze relationships between academic factors, detect outliers, and prepare categorical data for further machine learning applications.

The analysis was performed using Python libraries including **Pandas**, **Matplotlib**, and **Scikit-learn**.

---

## 🎯 Objectives

- Load and explore the student grading dataset
- Perform data cleaning and preprocessing
- Analyze statistical summaries
- Visualize relationships between academic features
- Identify possible outliers using the IQR method
- Encode categorical variables for machine learning readiness

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:** Students_Grading_Dataset.csv

The dataset contains information related to student academic performance, including:

- Attendance Percentage
- Study Hours per Week
- Final Score
- Gender
- Other student-related attributes

---

# 🔄 Data Analysis Workflow

## 1. Data Loading

The dataset was imported using Pandas:

```python
data = pd.read_csv("Students_Grading_Dataset.csv")
