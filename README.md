# 💰 Personal-Finance-Analysis-Forecasting-System

This project provides a complete analysis of personal expenses for the year 2024, offering insights into spending habits, key categories, and monthly trends. It leverages data science techniques to support better budgeting, identify unusual expenses, and forecast future spending patterns.

---

## 📊 Key Features

- **Data Cleaning & Preparation:**  
  Prepares and cleans personal expense data for reliable analysis.

- **Descriptive Statistics:**  
  Calculates total spending, category-wise distribution, and monthly totals.

- **Data Visualization:**  
  Includes pie charts and line graphs to visualize spending patterns and trends.

- **Time Series Analysis:**  
  Applies moving averages and seasonal decomposition to explore spending over time.

- **Statistical Analysis:**  
  Calculates 95% confidence intervals for typical monthly spending (excluding educational expenses) and detects outliers using Z-scores.

- **Summary Report Generation:**  
  Produces a comprehensive text-based report summarizing key findings and exporting the report as a `.txt` file.

---

## 📂 Files Included

- `Personal_Finance_Analysis.ipynb` : Jupyter Notebook containing the full analysis.
- `finance_summary.txt` : Automatically generated text report summarizing key insights.
- `Personal Expense Data.xlsx` : (Required) Excel file containing the expense data. Ensure it's placed in the same directory.

---

## 🛠 Technologies Used

- **Python Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `statsmodels`
  
- **Tools:**
  - Jupyter Notebook
  - Excel (for data source)

---

## 📌 Usage Instructions

1. **Prepare the Data:**
   - Ensure your Excel file (`Personal Expense Data.xlsx`) includes columns such as `Date`, `Category`, `Payment Method`, and `Amount`.
   - Place the Excel file in the same directory as the notebook.

2. **Run the Notebook:**
   - Open `Personal_Finance_Analysis.ipynb` in Jupyter Notebook.
   - Execute each cell sequentially to perform the analysis.

3. **Review the Results:**
   - Visualize charts and tables in the notebook.
   - Read the auto-generated summary report (`finance_summary.txt`).

---

## 📈 Conclusion

This project demonstrates how personal financial data can be analyzed using Python's data science stack to extract actionable insights. By combining descriptive statistics, visualizations, time series modeling, and statistical testing, the analysis uncovers patterns, anomalies, and forecasting insights that help in making informed financial decisions.

---

## 📃 License

This project is for personal and educational use only.
