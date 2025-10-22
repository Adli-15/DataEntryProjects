# 🧾 Employee Payroll Data Cleaning and Preprocessing (Malaysia)

This project focuses on cleaning and preprocessing a **synthetic Malaysian payroll dataset** using **Microsoft Excel**.  
It demonstrates practical data cleaning skills — identifying inconsistencies, handling missing values, converting data types, and preparing a dataset for further salary and HR analysis.

---

## 📊 Project Overview

Payroll data often contains errors such as missing salaries, text entries in numeric fields, or inconsistent job titles.  
This project simulates a realistic scenario using a **messy payroll dataset (2,000+ records)** representing employees across various Malaysian states, departments, and job roles.

The objective is to:
- Clean and standardize the dataset using **Excel tools**.
- Ensure data accuracy, consistency, and readiness for analysis.
- Derive meaningful insights such as **average salary by department or state**.

---

## 🧹 Tasks Performed

| Step | Task Description |
|------|------------------|
| 1 | Import CSV data into Excel and inspect structure |
| 2 | Identify missing and incorrect values (`error`, `unknown`, `NaN`) |
| 3 | Replace invalid entries and handle blanks using averages or estimates |
| 4 | Convert data types (text → numeric) for salary columns |
| 5 | Remove duplicate rows |
| 6 | Standardize text (state, department, job titles) |
| 7 | Add calculated fields: `Gross_Income`, `Total_Deductions`, `Net_Salary` |
| 8 | Detect and manage outliers using conditional formatting |
| 9 | Clean column names and format data for analysis |

---

## 🧠 Dataset Description

**Filename:** `malaysian_payroll_dataset_dirty.csv`  
**Size:** ~2,000 rows × 14 columns  

| Column Name | Description |
|--------------|-------------|
| Employee_ID | Unique identifier for each employee |
| Full_Name | Employee’s full name |
| Gender | Male or Female |
| Age | Employee’s age (some entries contain “unknown”) |
| Job_Title | Position title |
| Department | Functional department (HR, IT, Sales, etc.) |
| State | Malaysian state of employment |
| Basic_Salary_RM | Monthly base salary in RM (some invalid entries like “error”) |
| Allowances_RM | Monthly allowances in RM |
| Overtime_RM | Overtime payments |
| Bonus_RM | Annual/quarterly bonus amount |
| EPF_Deduction_RM | Employee provident fund deduction |
| SOCSO_Deduction_RM | SOCSO contribution deduction |
| Joining_Date | Employment start date |

---

## ⚙️ Tools Used
- **Microsoft Excel** – primary tool for cleaning and preprocessing  
- **Data Validation, Remove Duplicates, Find & Replace, Conditional Formatting**  
- **Formulas used:**  
  - `=IFERROR(VALUE(A2), "")` – fix non-numeric salary data  
  - `=PROPER(A2)` – standardize text capitalization  
  - `=AVERAGEIF()` – replace missing values  
  - `=Basic_Salary_RM + Allowances_RM + Overtime_RM + Bonus_RM` – calculate Gross Income  
  - `=Gross_Income - (EPF_Deduction_RM + SOCSO_Deduction_RM)` – calculate Net Salary  

---

## 📈 Outcome

After cleaning, the dataset became fully analyzable with:
- Consistent data types  
- No duplicate or missing salary values  
- Correct capitalization and uniform formatting  
- New computed columns for gross and net pay  

This cleaned dataset can now be used for:
- Salary distribution analysis  
- Gender or state-based pay comparisons  
- HR analytics dashboards  

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `malaysian_payroll_dataset_dirty.csv` | Original unclean dataset |
| `malaysian_payroll_dataset_cleaned.xlsx` | Final cleaned version |
| `README.md` | Project documentation |

---

## 📚 Learning Highlights
- Real-world data cleaning using Excel only  
- Practical handling of text-to-number conversion and invalid entries  
- Building calculated payroll fields for analysis  
- Understanding payroll components in a Malaysian context (EPF, SOCSO)

---

## 🧩 Future Improvements
- Automate cleaning using Python (pandas)  
- Visualize salary trends using Power BI or Excel charts  
- Add department-based dashboards or KPI tracking  

---

### ✨ Author
**Adli Asri**  
📍 Malaysia  
📧 [adli_asri15@yahoo.com](mailto:adli_asri15@yahoo.com)

---

> “Clean data leads to clear insights.”