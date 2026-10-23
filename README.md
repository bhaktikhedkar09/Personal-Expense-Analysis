# Personal Expense Analysis — Python Mini Project

## Aim
To clean, analyze, and visualize personal expense records using Pandas, NumPy, Matplotlib, and Seaborn.

## Project files
- `personal_expenses.csv` — sample transaction dataset (includes a few intentional data-quality issues for cleaning practice).
- `expense_analysis.py` — complete runnable Python program.
- `requirements.txt` — required Python libraries.
- `brief_report.md` — ready-to-edit project report.
- `outputs/` — generated charts, cleaned data, summaries (created after running the script).

## Run on Windows
1. Install Python 3.10 or newer.
2. Open Command Prompt in this project folder.
3. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```
4. Run:
   ```bash
   python expense_analysis.py
   ```
5. Check the `outputs` folder for six PNG charts, cleaned CSV, summary tables, and text summary.

## Methods demonstrated
- Pandas: reading CSV, standardizing labels, parsing dates, handling missing values, removing duplicate rows, grouping and aggregating.
- NumPy: sum, mean, median, standard deviation, minimum, and maximum.
- Matplotlib/Seaborn: category bar chart, monthly trend line, category share pie chart, payment method comparison, histogram, and needs-vs-wants comparison.

## Dataset note
The included records are synthetic and intended for demonstration, not real personal financial records.
