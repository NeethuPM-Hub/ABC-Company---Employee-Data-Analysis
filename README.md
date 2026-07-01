# Employee Data Analysis – ABC Company

## Project Overview

This project analyzes the **ABC Company Employee Dataset**, which contains **458 employee records** with **9 columns**. The objective of the project is to preprocess the dataset, perform exploratory data analysis (EDA), and visualize key insights using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Dataset Information

The dataset contains information about employees, including:

* Name
* Team
* Position
* Age
* Height
* Weight
* College
* Salary
* Number

---

## Data Preprocessing

The following preprocessing steps were performed before analysis:

* Loaded the dataset using Pandas.
* Replaced the **Height** column with randomly generated values between **150 cm and 180 cm** to ensure data consistency.
  

---

## Analysis Performed

### 1. Employee Distribution Across Teams

* Calculated the total number of employees in each team.
* Computed the percentage contribution of each team relative to the total workforce.

### 2. Employee Distribution by Position

* Grouped employees according to their job positions.
* Counted the number of employees in each position.

### 3. Predominant Age Group

* Divided employee ages into age groups.
* Identified the age group containing the highest number of employees.

### 4. Salary Expenditure Analysis

* Calculated the total salary expenditure for each team.
* Calculated the total salary expenditure for each position.
* Identified the team and position with the highest salary expenditure.

### 5. Correlation Between Age and Salary

* Investigated the relationship between employee age and salary.
* Calculated the correlation coefficient.
* Visualized the relationship using a scatter plot.

---

## Visualizations

The following visualizations were created using Matplotlib and Seaborn:

* Bar Chart – Employee Distribution Across Teams
* Bar Chart – Employee Distribution by Position
* Bar Chart – Employee Distribution by Age Group
* Bar Chart – Salary Expenditure by Team
* Bar Chart – Salary Expenditure by Position
* Scatter Plot – Age vs. Salary Correlation

---

## Key Insights

* The employees are distributed across multiple teams, most of the teams are having equal employees.
* Employees are distributed across different positions, Every position is having 60+ Employees.
* Most of the employees belong to the 20–29 age group. The number of employees decreases as the age group increases.
* The charts identify the Team & Position with the highest total salary expenditure. Team with Highest Salary is Charlotte Hornets & Position with Highest salary is C.
* There is a slight positive relationship between age and salary, with salaries tending to increase as age increases.

---

## Project Structure

```text
Employee-Data-Analysis/
│── ABC_company.csv
│── Employee_Data_Analysis.ipynb
│── README.md
```

---

## Conclusion

This project demonstrates the complete workflow of data analysis, including data preprocessing, exploration, visualization, and interpretation. It provides meaningful insights into employee distribution, salary expenditure, and age-related trends using Python's data analysis libraries.

---

## Author

**Neethu Mohan**

