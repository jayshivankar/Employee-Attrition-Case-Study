# 📊 Exploratory Data Analysis - Employee Dataset

This repository contains an Exploratory Data Analysis (EDA) project on an Employee dataset. The aim of this project is to uncover patterns and insights within the data that can help organizations make informed HR decisions.

## 📁 Dataset Overview

The dataset used in this analysis is `employee_data.csv`, which includes various attributes related to employee demographics, job details, and employment status.

### 🔍 Example Features (may include)

- `EmployeeID`: Unique identifier for each employee
- `Name`: Employee name
- `Age`: Age of the employee
- `Gender`: Gender identity
- `Department`: Department where the employee works
- `JobRole`: Specific role or designation
- `Education`: Highest level of education
- `MaritalStatus`: Marital status
- `MonthlyIncome`: Income per month
- `YearsAtCompany`: Tenure in years
- `Attrition`: Whether the employee has left the company (Yes/No)

## 🧪 EDA Process

The EDA was performed using Python and Jupyter Notebook. The analysis steps include:

### 1. Data Cleaning
- Identified and handled missing values
- Standardized categorical variables
- Converted data types where appropriate

### 2. Univariate Analysis
- Analyzed distributions of numerical variables
- Visualized counts of categorical variables using bar plots

### 3. Bivariate/Multivariate Analysis
- Explored relationships between variables such as:
  - Income vs Job Role
  - Attrition rate by Department, Age, and Gender
- Correlation matrix of numeric variables

### 4. Key Insights
- Certain departments or job roles have higher attrition rates
- Younger employees and those with fewer years at the company are more likely to leave
- Monthly income and education levels show notable trends across departments

### 5. Visualizations
- Bar plots of attrition by job role and department
- Histograms of age and income distribution
- Heatmap of feature correlations

## 📂 Project Structure

```bash
├── data/
│   └── employee_data.csv
├── eda/
│   └── employee_eda.ipynb
├── images/
│   ├── attrition_by_department.png
│   ├── income_distribution.png
│   └── correlation_heatmap.png
├── README.md
```

## 🛠 Tools Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- NumPy

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/employee-eda.git
cd employee-eda
```

2. Launch the EDA notebook:
```bash
jupyter notebook eda/employee_eda.ipynb
```

## 📌 Notes

- This is an EDA-only project and does not include any predictive modeling.
- Results are intended for insights and internal reporting.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute or fork the repo for your own analysis!
