# 📊 Student Performance Analysis

## 📌 Project Overview

This project analyzes student performance data to understand factors associated with academic performance, identify students who may need additional support, and provide actionable recommendations.

The analysis is performed using Python and focuses on parental education, test preparation, gender, subject-score relationships, and total score distribution.

---

## 🎯 Problem Statement

The school wants to understand the factors related to student academic performance. This project analyzes student scores, identifies at-risk students, and provides recommendations that can help the school provide better academic support.

---

## 🎯 Objectives

- Explore and understand the student performance dataset.
- Check and clean the data.
- Analyze factors associated with student scores.
- Compare performance across different student groups.
- Identify at-risk students.
- Create meaningful visualizations.
- Provide actionable recommendations.

---

## 📂 Dataset

**Dataset:** Students Performance in Exams

The dataset contains **1,000 student records** and **8 columns**.

### Important Columns

| Column | Description |
|---|---|
| `gender` | Gender of the student |
| `race/ethnicity` | Race/ethnicity group |
| `parental level of education` | Parent's education level |
| `lunch` | Type of lunch received |
| `test preparation course` | Test preparation status |
| `math score` | Mathematics score |
| `reading score` | Reading score |
| `writing score` | Writing score |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code
- GitHub

---

## 🔍 Analysis Performed

The project answers five main questions:

1. How do scores vary across parental education levels?
2. Do students who completed test preparation have higher scores?
3. What is the relationship between Math, Reading, and Writing scores?
4. How does performance differ by gender across subjects?
5. What is the distribution of students' total scores?

---

## 📊 Visualizations

The project includes six visualizations:

- Box Plot – Math Scores by Parental Education
- Bar Chart – Test Preparation vs Average Scores
- Correlation Heatmap – Subject Scores
- Grouped Bar Chart – Gender vs Subject Performance
- Histogram – Total Score Distribution
- Scatter Plot – Reading Score vs Math Score

All visualizations are included in the Jupyter Notebook.

---

## 🚨 At-Risk Student Segmentation

For this project, a student is classified as **at-risk if they score below 50 in at least one subject**.

### Results

| Category | Count |
|---|---:|
| Total Students | 1,000 |
| At-Risk Students | 188 |
| At-Risk Percentage | 18.8% |

The analysis also compares at-risk percentages across gender, parental education, and test preparation groups.

---

## 📌 Key Findings

- Average scores vary across different parental education levels.
- Students who completed test preparation had higher average scores in all three subjects.
- Reading and Writing scores showed the strongest positive correlation (**0.955**).
- Male students had a higher average Math score, while female students had higher average Reading and Writing scores.
- **188 out of 1,000 students (18.8%)** were classified as at-risk.

---

## 🏫 Recommendations

1. Provide **extra academic support** for at-risk students.
2. Encourage students to **complete test preparation courses**.
3. Conduct **regular assessments** to identify struggling students early.

---

## 📁 Project Structure

```text
Student_Performance_Analysis/
│
├── Data/
│   └── StudentsPerformance.csv
│
├── Notebook/
│   ├── Project_Intro.ipynb
│   └── Student_Performance_Analysis.ipynb
│
├── README.md
