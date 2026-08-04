# AI_Project_Learning_Student_Performance_Analysis
# 🎓 Student Performance Analysis System

### Python, Pandas & NumPy Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge\&logo=numpy)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge\&logo=github)

---

## 📖 Overview

This project is a **Student Performance Analysis System** developed using **Python, Pandas, and NumPy**.

The project analyzes a dataset containing information about **500 students**. It demonstrates how Python can be used to load, explore, select, filter, and perform numerical operations on student performance data.

The project focuses on practical use of:

* Pandas DataFrames
* Column selection
* Row selection
* Conditional filtering
* NumPy arrays
* Basic statistical calculations
* Student performance reporting

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Load a CSV dataset using Pandas.
* Explore the student dataset.
* Identify the number of students and departments.
* Display and select specific columns.
* Select specific rows using `iloc` and `loc`.
* Filter students according to different conditions.
* Perform numerical calculations using NumPy.
* Calculate maximum, minimum, and average marks.
* Generate a final Student Performance Report.

---

## 🗃️ Dataset

The project uses the following dataset:

```text
students_performance_dataset_500.csv
```

The dataset contains information about **500 students**.

The analysis uses student information such as:

* Name
* Department
* Gender
* Age
* Attendance
* Quiz Marks
* Final Marks

---

## 📂 Project Structure

```text
Student_Performance_Analysis/
│
├── Student_Performance_Analysis_Complete.py
├── students_performance_dataset_500.csv
└── README.md
```

### Files Description

| File                                       | Description                                          |
| ------------------------------------------ | ---------------------------------------------------- |
| `Student_Performance_Analysis_Complete.py` | Main Python program containing the complete solution |
| `students_performance_dataset_500.csv`     | Student performance dataset                          |
| `README.md`                                | Project documentation                                |

---

# 📌 Assignment Tasks

## Part 1 — Loading the Dataset

The first part of the project focuses on loading and inspecting the CSV dataset.

The program:

1. Loads the CSV dataset into a Pandas DataFrame.
2. Displays the first five rows.
3. Displays the last five rows.
4. Displays the total number of rows and columns.
5. Displays all column names.

---

## Part 2 — Exploring the Dataset

This section explores basic information about the students.

The program:

6. Finds the total number of students.
7. Finds the total number of unique departments.
8. Displays all department names.
9. Finds the total number of male students.
10. Finds the total number of female students.

---

## Part 3 — Column Selection

This section demonstrates how to select specific columns from a Pandas DataFrame.

The program:

11. Displays only the `Name` column.
12. Displays `Name`, `Department`, and `Final_Marks`.
13. Displays `Name` and `Attendance`.

---

## Part 4 — Row Selection

This section demonstrates row selection using Pandas `iloc` and `loc`.

The program:

14. Displays the first student using `iloc[0]`.
15. Displays the fifth student using `iloc[4]`.
16. Displays the last student using `iloc[-1]`.
17. Displays the student at index label `20` using `loc[20]`.
18. Displays the student at index label `100` using `loc[100]`.

---

## Part 5 — Conditional Selection

This section demonstrates filtering using conditions.

The program displays:

19. Students whose `Final_Marks` are greater than 40.
20. Students whose `Attendance` is greater than 90.
21. Students belonging to the `AI` department.
22. Students belonging to the `CS` department.
23. Students whose `Age` is greater than 21.
24. Students whose `Quiz_Marks` are greater than 15.

---

## Part 6 — NumPy Operations

NumPy is used for numerical operations on the `Final_Marks` column.

The program:

28. Finds the maximum Final Marks.
29. Finds the minimum Final Marks.
30. Calculates the average Final Marks.
31. Calculates the square root of every Final Mark.
32. Multiplies every Final Mark by 2.
33. Converts Final Marks into the float data type.

---

# 📊 Final Student Performance Report

The program generates a final summary containing:

* Total Students
* Total Departments
* Average Attendance
* Average Final Marks
* Highest Final Marks
* Lowest Final Marks

Using the provided dataset, the final report is:

```text
========================================
Student Performance Report
========================================
Total Students       : 500
Total Departments    : 5
Average Attendance   : 77.068 %
Average Final Marks  : 35.08
Highest Final Marks  : 50
Lowest Final Marks   : 20
========================================
```

---

# 🛠️ Technologies Used

| Technology | Purpose                                           |
| ---------- | ------------------------------------------------- |
| Python     | Main programming language                         |
| Pandas     | Loading, exploring, selecting, and filtering data |
| NumPy      | Numerical and mathematical operations             |
| CSV        | Dataset format                                    |
| VS Code    | Code development and execution                    |
| GitHub     | Repository hosting and submission                 |

---

# 📦 Python Libraries

The project uses two main libraries:

```python
import pandas as pd
import numpy as np
```

### Pandas

Pandas is used to:

* Read the CSV file.
* Create a DataFrame.
* Select columns.
* Select rows.
* Filter data.
* Explore the dataset.

### NumPy

NumPy is used to:

* Calculate maximum values.
* Calculate minimum values.
* Calculate averages.
* Calculate square roots.
* Perform array multiplication.
* Convert data types.

---

# 🚀 How to Run the Project

## Step 1 — Install Python

Make sure Python is installed on your computer.

Check the installation by running:

```bash
python --version
```

---

## Step 2 — Install Required Libraries

Open the terminal in VS Code and run:

```bash
pip install pandas numpy
```

---

## Step 3 — Keep the Files Together

Make sure the following two files are inside the same folder:

```text
Student_Performance_Analysis_Complete.py
students_performance_dataset_500.csv
```

This is important because the Python program loads the dataset using:

```python
pd.read_csv("students_performance_dataset_500.csv")
```

---

## Step 4 — Run the Program

Open the Python file in **VS Code**.

Click the **Run Python File** button or run:

```bash
python Student_Performance_Analysis_Complete.py
```

---

## Step 5 — View the Output

The program displays:

* Dataset rows
* Dataset columns
* Student counts
* Department information
* Selected columns
* Selected students
* Filtered students
* NumPy calculations
* Final Student Performance Report

---

# 💡 Skills Demonstrated

This project demonstrates the following programming and data analysis skills:

* Python programming
* Pandas DataFrame handling
* CSV file handling
* Data exploration
* Column selection
* Row selection
* `iloc`
* `loc`
* Conditional filtering
* NumPy arrays
* Mathematical operations
* Basic statistical analysis
* Data reporting
* GitHub project organization

---

# 📈 Learning Outcomes

After completing this project, I learned how to use **Pandas and NumPy for basic data analysis**.

I learned how to load a CSV dataset, explore its information, select specific rows and columns, filter data according to conditions, and perform numerical calculations.

The project also helped me understand how Python can be used to analyze student performance data and create a simple performance report.

---

# 👨‍🎓 Student Information

**Name:** Ali Raza

**Roll Number:** 1006

**Section:** AI & ML

**Course:** Artificial Intelligence — Machine Learning & Deep Learning

---

# 📌 Conclusion

The **Student Performance Analysis System** provides practical experience with Python, Pandas, and NumPy.

By working with a dataset of 500 students, the project demonstrates important data analysis techniques including data loading, exploration, selection, filtering, numerical calculations, and report generation.

This project provides a foundation for more advanced data analysis, machine learning, and artificial intelligence projects.

---

<div align="center">

### 🎓 Student Performance Analysis System

**Built with Python, Pandas & NumPy**

</div>
