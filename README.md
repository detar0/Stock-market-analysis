# 📈 Stock Price Analysis: NVIDIA, Google, Apple

This project analyzes the historical stock price trends of three major tech companies: **NVIDIA (NVDA)**, **Google (GOOGL)**, and **Apple (AAPL)**. Using Python, the notebook explores data cleaning, SQL querying, and data visualization techniques to uncover long-term performance patterns.

## 🔍 What's Inside?
- Loading and preprocessing stock data (Open, High, Low, Close, Volume).
- Calculating average daily price: `(High + Low) / 2`.
- Storing data in a SQLite database using `df.to_sql()`.
- Querying data with SQL:
  - Extracting years with `strftime("%Y", Date)`
  - Filtering with `BETWEEN 2005 AND 2025`
  - Grouping and sorting using `GROUP BY` and `ORDER BY`
- Visualizing trends with **seaborn** and **matplotlib**:
  - Line plots of stock performance over time
  - Custom annotations and styled legends

## 🛠️ Technologies Used
- Python
- Pandas
- Jupyter Notebook
- SQLite (`sqlite3`)
- Seaborn & Matplotlib

## 🖼 Preview
[Line Plot](images/lineplot.png)
