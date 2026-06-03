# HR Employee Attrition Analysis

Tools: Python, Pandas, NumPy, Matplotlib, Seaborn  
Dataset: IBM HR Analytics Employee Attrition (Kaggle)  
Environment: Jupyter Notebook / Google Colab

## Project Overview
Analysed an HR dataset of 1,470 employees to understand workforce 
patterns and identify which departments have the highest employee 
attrition. This project covers data loading, cleaning, exploration, 
and visualization.

## What I Did
- Loaded and explored the dataset (1,470 rows, 35 columns)
- Checked for missing values using both code and a heatmap
- Identified and dropped 3 useless columns with only one unique value
- Checked for duplicate rows
- Explored data types, distributions, and key column splits
- Built 5 visualizations to answer real business questions

## Business Questions Answered
| Question | Finding |
|---|---|
| How many employees left? | 16.1% attrition rate (237 out of 1,470) |
| Which dept has highest attrition? | Sales at 20.6% |
| Does R&D really have the worst attrition? | No — it just has the most people |
| What is the age spread? | 18 to 60, average age 37 |
| How is salary distributed? | Wide gap — 1,009 to 19,999 USD |

## Key Findings
- Sales department has the highest attrition **rate** at 20.6%
- R&D looks worst by raw count but has the lowest rate at 13.8%
- Raw counts vs percentage rates tell completely different stories
- Large income inequality exists across the workforce

## What I Learned
- Data cleaning is not just about missing values — useless columns matter too
- Always use rates not raw counts when comparing groups of different sizes
- `groupby` + `unstack` is powerful for comparing categories
- Writing comments in code helps explain decisions to others

## Files
- `hr_employee_attrition.ipynb` — full analysis notebook
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — dataset

## Connect
- LinkedIn: www.linkedin.com/in/sandip-subedi-5694b136a
- Hashnode: https://hashnode.com/@sandipsubedi0
- Instagram : https://www.instagram.com/sandipsubedi0/
