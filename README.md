🐍 Capstone Project – Python Fundamentals

📌 Project Overview

This project demonstrates my understanding of Python fundamentals, data manipulation, and problem-solving using Pandas and NumPy.
The dataset simulates an organizational setup with Employees, Seniority Levels, and Projects, and the tasks focus on cleaning, transforming, and analyzing the data.

The project is implemented step by step with clearly commented code in a Jupyter Notebook (.ipynb).

📂 Dataset Explanation
Employee DataFrame
| ID   | Name            | Gender | City    | Age |
| ---- | --------------- | ------ | ------- | --- |
| A001 | John Alter      | M      | Paris   | 25  |
| A002 | Alice Luxumberg | F      | London  | 27  |
| A003 | Tom Sabestine   | M      | Berlin  | 29  |
| A004 | Nina Adgra      | F      | Newyork | 31  |
| A005 | Amy Johny       | F      | Madrid  | 30  |

Seniority Level DataFrame
| ID   | Designation Level |
| ---- | ----------------- |
| A001 | 2                 |
| A002 | 2                 |
| A003 | 3                 |
| A004 | 2                 |
| A005 | 3                 |

Project DataFrame
| ID   | Project    | Cost    | Status   |
| ---- | ---------- | ------- | -------- |
| A001 | Project 1  | 1002000 | Finished |
| A002 | Project 2  | 2000000 | Ongoing  |
| A003 | Project 3  | 4500000 | Finished |
| A004 | Project 4  | 5500000 | Ongoing  |
| A005 | Project 5  | NaN     | Finished |
| A002 | Project 6  | 680000  | Failed   |
| A005 | Project 7  | 400000  | Finished |
| A003 | Project 8  | 350000  | Failed   |
| A001 | Project 9  | NaN     | Ongoing  |
| A003 | Project 10 | 300000  | Finished |
| A001 | Project 11 | 2000000 | Failed   |
| A004 | Project 12 | 1000000 | Ongoing  |
| A004 | Project 13 | 3000000 | Finished |
| A005 | Project 14 | 200000  | Finished |

📝 Tasks

✅ Task 1

Create three DataFrames in Python and save them as .csv files.

✅ Task 2

Fill missing values in the Project Cost column using running average (with a for loop).

✅ Task 3

Split the Name column into First Name and Last Name, then remove the original column.

✅ Task 4

Merge all three DataFrames into a single Final DataFrame.

✅ Task 5

Add a Bonus column (5% of project cost) for employees who have finished projects.

✅ Task 6

Demote designation level by 1 for employees with Failed projects.

Delete employees with designation level > 4.

✅ Task 7

Prefix Mr./Mrs. to first names and drop the Gender column.

✅ Task 8

Promote designation level by 1 for employees whose Age > 29.

✅ Task 9

Create a new DataFrame TotalProjCost with columns:
ID | First Name | Total Cost

✅ Task 10

Print all employees whose City contains the letter "o".

📊 Performance Evaluation

The project uses:

Python Fundamentals (loops, conditionals, string manipulation)

Pandas for DataFrame operations

NumPy for numerical tasks

This capstone demonstrates how to clean, transform, merge, and analyze datasets – key skills for a Data Analyst / Data Scientist role.

🚀 Deliverables

Jupyter Notebook (Capstone_Project.ipynb) with code + outputs + comments

CSV files for Employee, Seniority Level, and Project data
