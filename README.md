# 📊 Employee Data Analysis

> Exploratory data analysis and business insights using **Python** & **Pandas**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Latest-orange?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-purple?style=flat-square&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

---

## 📌 Overview

This project performs end-to-end **Exploratory Data Analysis (EDA)** on an employee dataset using Python and Pandas. It covers data cleaning, transformation, and generating actionable business insights — all inside a clean Jupyter Notebook.

---

## 🗂️ Project Structure

```
employee-data-analysis/
│
├── 📓 employee_analysis.ipynb   # Main Jupyter Notebook
├── 📁 data/
│   └── employees.csv            # Sample employee dataset
├── 📁 outputs/
│   └── insights_report.csv      # Exported results
└── 📄 README.md
```

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/yourname/employee-data-analysis.git
cd employee-data-analysis

# 2. Install dependencies
pip install pandas jupyter

# 3. Launch the notebook
jupyter notebook employee_analysis.ipynb
```

---

## 🧹 Data Cleaning

| Step | Description |
|------|-------------|
| ✅ Department names | Standardised case-insensitive dept labels |
| ✅ Missing salaries | Imputed using department-level mean |
| ✅ Data types | Verified and corrected column dtypes |
| ✅ Duplicates | Checked and removed duplicate records |

---

## 📊 Analysis Performed

- **Average salary** — company-wide and per department
- **Highest & lowest earners** — top and bottom salary identification
- **Department-wise breakdown** — salary distribution across teams
- **City-wise distribution** — employee headcount by location
- **High earner filter** — employees above salary threshold

---

## 🔍 Key Insights

### 💼 Software leads in salary
> The **Software department** has the highest average salary — approximately **34% above** the company average.

### 🏙️ Mumbai dominates headcount
> **Mumbai** hosts the largest employee population, followed by Bangalore and Pune.

### 📈 Experience drives pay
> Employees with **8+ years** of experience earn on average **2.3×** more than those with under 2 years.

---

## 📉 Salary Index by Department

```
Software   ████████████████████  100%
Finance    █████████████████░░░   87%
Marketing  █████████████░░░░░░░   68%
HR         ████████████░░░░░░░░   63%
Operations ██████████░░░░░░░░░░   54%
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| 🐍 Python 3 | Core programming language |
| 🐼 Pandas | Data manipulation & analysis |
| 📓 Jupyter Notebook | Interactive development environment |

---

## 📁 Dataset

A sample employee dataset was created for this analysis containing:
- Employee name, department, city
- Salary (with intentional missing values for cleaning practice)
- Years of experience

---

## 📌 Conclusion

This project demonstrates a complete **data analytics workflow** — from raw messy data to clean, analysed, and insight-ready output using Pandas. Ideal as a reference for beginner to intermediate data analysis projects.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ using Python & Pandas</p>
