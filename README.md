# 📊 HR Analytics — Exploratory Data Analysis

An Exploratory Data Analysis (EDA) project focused on analyzing **employee engagement, performance, salary, recruitment, satisfaction, attendance, and workforce-related patterns** using Python.

The goal of this project is to explore HR employee data, identify meaningful patterns, and generate insights that can help understand employee performance and engagement.

---

## 🎯 Project Objective

The main objective of this project is to perform EDA on an HR employee dataset and answer important questions related to:

* Employee salary distribution
* Employee performance
* Employee satisfaction
* Employee engagement
* Absence patterns
* Recruitment sources
* Special project participation
* Department-wise salary and engagement
* Employee termination patterns
* Gender and marital-status distribution

---

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Development environment

---

## 📂 Dataset

The project uses the **HRDataset_v14.csv** dataset containing employee-related information.

The dataset includes attributes related to:

* Employee information
* Salary
* Department
* Position
* Performance
* Employee satisfaction
* Engagement
* Absences
* Recruitment source
* Special projects
* Termination information
* Gender and marital status

---

## 🔄 Data Preparation

Before performing the analysis, the dataset was inspected and cleaned.

### Steps performed:

1. Loaded the dataset using Pandas.
2. Examined dataset shape and columns.
3. Checked data types and dataset information.
4. Identified missing values.
5. Handled missing values.
6. Checked for duplicate records.
7. Removed duplicate records where required.
8. Performed exploratory analysis on relevant variables.

---

## 🔍 Exploratory Data Analysis

The analysis covers several HR-related questions.

### 💰 Salary Analysis

* Identified the top 10 highest-paid employees.
* Compared the highest and lowest salary ranges.
* Analyzed salary distribution across departments.
* Examined salary outliers using box plots.
* Compared median salary between male and female employees.

### 📈 Employee Performance

* Analyzed employee performance scores.
* Identified employees under **Performance Improvement Plan (PIP)**.
* Examined the distribution of performance scores.

### 😊 Employee Satisfaction & Engagement

* Analyzed employee satisfaction ratings.
* Studied engagement scores across different positions.
* Calculated the average engagement score for each department.
* Compared engagement levels across departments.

### 🏖️ Absence Analysis

* Examined employee absence patterns.
* Calculated absence frequencies and percentages.
* Analyzed total absences by department.
* Compared average absences across gender categories.

### 📢 Recruitment Analysis

Analyzed the different sources through which employees were recruited.

The analysis showed that **Indeed was the most common recruitment source**, followed by LinkedIn and Google Search in the dataset.

### 🏆 Special Projects

* Identified employees participating in special projects.
* Analyzed employees with no special-project participation.
* Calculated the total number of special projects by gender.

### 👥 Workforce Demographics

Analyzed:

* Gender distribution
* Marital status
* Marital status by gender
* Employee satisfaction
* Department-wise workforce characteristics

### 🚪 Termination Analysis

Analyzed terminated employees based on:

* Position
* Termination reason

This helps explore workforce turnover patterns within the dataset.

---

## 📊 Visualizations

Several visualizations were created using **Matplotlib and Seaborn**, including:

* Bar charts
* Horizontal bar charts
* Line plots
* Stem plots
* Box plots
* Count plots
* Department-wise salary analysis
* Position-wise engagement analysis

These visualizations were used to identify patterns and communicate the findings more clearly.

---

## 💡 Key Insights

Some important findings from the analysis include:

* The highest salaries show greater variation compared with the lowest salaries.
* Some departments contain noticeable salary outliers.
* The **Executive Office** shows the highest average engagement score among departments.
* **Indeed** is the most common recruitment source in the dataset.
* The most common employee satisfaction rating is **3**.
* Employees under the **PIP (Performance Improvement Plan)** were identified for further attention.
* Employees with no special-project participation were identified.
* Salary levels vary considerably across departments and positions.
* Termination patterns were explored across different positions and termination reasons.

> **Note:** These insights are based specifically on the dataset used in this notebook and should not be generalized to all organizations.

---

## 📌 Analysis Questions

The project also explores questions such as:

* Who are the highest-paid employees?
* Which employees require performance-related attention?
* What are the most common absence levels?
* Which recruitment source hires the most employees?
* What is the distribution of employee satisfaction?
* Which departments have higher salary levels?
* What is the average engagement score by department?
* How many employees were terminated from each position?
* What are the major termination reasons?
* What is the median salary by gender?
* How do absences and special projects vary by gender?

---

## 🚀 Skills Demonstrated

Through this project, the following skills were practiced:

**Python**

* Data loading
* Data cleaning
* Data filtering
* Sorting
* GroupBy
* Aggregation
* Descriptive analysis
* Duplicate handling

**Pandas**

* DataFrame manipulation
* Conditional filtering
* `groupby()`
* `agg()`
* `value_counts()`
* Missing-value handling

**Data Visualization**

* Matplotlib
* Seaborn
* Comparative charts
* Distribution analysis
* Multivariate visualization

**EDA**

* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* Insight generation

---

## 📁 Project Structure

```text
HR-Analytics-EDA/
│
├── EDA-HR Analytics.ipynb
├── HRDataset_v14.csv
└── README.md
```

---

## 📌 Conclusion

This project demonstrates how **Python-based Exploratory Data Analysis** can be used to understand employee-related data and uncover patterns in salary, performance, engagement, satisfaction, attendance, recruitment, and workforce characteristics.

The project also provides practical experience with **Pandas, NumPy, Matplotlib, Seaborn, data cleaning, visualization, aggregation, and insight generation**.

---

## 👨‍💻 Author

**Tanmoy Dey**

Aspiring Data Analyst / Data Science Enthusiast

**Tools:** Python • Pandas • NumPy • Matplotlib • Seaborn • Jupyter Notebook
