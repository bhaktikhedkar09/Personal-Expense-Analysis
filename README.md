# Personal Expense Analysis — Python Mini Project

## Aim
To clean, analyze, and visualize personal expense records using Pandas, NumPy, Matplotlib, and Seaborn.

## Project Files
- `personal_expenses.csv` — sample transaction dataset with intentional data-quality issues for cleaning practice.
- `expense_analysis.py` — complete runnable Python program.
- `requirements.txt` — required Python libraries.
- `brief_report.md` — project report.
- `outputs/` — generated charts, cleaned data, and summary files.

## Run on Windows

1. Install Python 3.10 or newer.
2. Open PowerShell or Command Prompt in this project folder.
3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Run the program:

   ```bash
   python expense_analysis.py
   ```

5. Check the `outputs` folder for six charts, cleaned data, summary tables, and the text summary.

## Methods Demonstrated

- **Pandas:** Reading CSV files, standardizing labels, parsing dates, handling missing values, removing duplicate rows, grouping, and aggregation.
- **NumPy:** Sum, mean, median, standard deviation, minimum, and maximum.
- **Matplotlib and Seaborn:** Category bar chart, monthly spending trend, category share pie chart, payment method comparison, transaction amount histogram, and needs-versus-wants comparison.

## Dataset Note
The included records are synthetic and intended for demonstration, not real personal financial records.
