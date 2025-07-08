# Online Course Dashboard
This project aims to analyze student performance and engagement on an online course platform using a dataset of 1,200 student records. The primary objective is to uncover insights into learning behavior, course completion trends, and feedback patterns, which can help improve student retention, course design, and overall learning experience.

## 🧹 Data Cleaning (Excel)

The dataset initially contained multiple inconsistencies, missing values, and formatting issues. Data cleaning was performed entirely in Microsoft Excel using functions, filters, and formulas. 

### Key cleaning steps:

#### 1. Name Formatting
Corrected case inconsistencies in names, removed extra spaces, and ensured **proper** formatting.

#### 2. Email Validation
Identified and flagged missing or malformed email addresses.

#### 3. Progress & Time Spent
Cleaned percentage formats, standardized time units into consistent **hours** format.

#### 4. Age Validation
Imputed invalid or missing ages with **Median imputation**.

#### 5. Feedback Cleaning
Filtered out-of-range feedback scores and handled blanks.

#### 6. High Performer Flag
Highlighted the student ID of the students who completed the course and have a rating of≥ 4.

#### 7. New Derived Columns
Experience_Level column based on age: Student, Early Career, etc.

Engagement Level column based on Time Spent + Progress


## 📊 Visualization & Analysis (Power BI):
Cleaned data was imported into Power BI to build an interactive dashboard and conduct exploratory analysis.

### 1. Dashboard Page

![1](https://github.com/user-attachments/assets/0589ba48-6d05-48a4-999c-4b76d7fa2b3c)

### 2. Details Page

![2](https://github.com/user-attachments/assets/9a727cab-b79b-4839-bac6-79a484e844bb)

### 2. Ratings Page
![3](https://github.com/user-attachments/assets/95c659f8-1e29-49de-b613-89ec9af46a72)


## 🎯 Outcome:
The project provides valuable insights into how learners engage with the platform and what factors influence course completion and satisfaction. These findings can inform strategies for personalized learning paths, course design improvements, and targeted interventions for at-risk students.

