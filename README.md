

# 🏦 Best Stock Buy

> A data-driven stock analysis tool that scrapes real-time financial data and identifies the best investment opportunities using Python-based web scraping and analytics.

---

## 📖 Overview

**Best Stock Buy** is a Python project that leverages web scraping and financial analysis to assist investors in identifying undervalued and high-growth stocks.  
By collecting and analyzing data from **[screener.in](https://www.screener.in)**, the tool filters stocks using key metrics like:

- **Price-to-Earnings (P/E) Ratio**
- **Return on Capital Employed (ROCE)**
- **Sales Growth**
- **Profit Growth**

The output includes data visualizations, styled tables, and CSV reports that simplify the process of choosing the right stocks for investment.

---

## 🎯 Objectives

- Automate financial data collection using web scraping.  
- Analyze and filter stocks based on predefined investment criteria.  
- Provide visual insights and structured data for better decision-making.  
- Enable investors to identify undervalued stocks with strong fundamentals.

---

## ⚙️ Tech Stack & Tools

| Category | Technologies |
|-----------|---------------|
| Programming | Python 3.x |
| Libraries | `requests`, `BeautifulSoup4`, `pandas`, `matplotlib` |
| Environment | Jupyter Notebook / Google Colab |
| Data Source | [Screener.in](https://www.screener.in) |

---

## 🧠 Methodology

1. **Data Extraction:**  
   Uses `requests` to fetch HTML content and `BeautifulSoup` to parse stock data from screener.in.

2. **Data Processing:**  
   Stores and cleans extracted data in a `pandas` DataFrame.

3. **Analysis:**  
   Computes and compares financial metrics such as P/E ratio, ROCE, and growth percentages.

4. **Filtering:**  
   Applies investment filters to identify top-performing or undervalued stocks.

5. **Visualization:**  
   Generates charts (bar/scatter plots) using `matplotlib` for intuitive interpretation.

6. **Export:**  
   Saves final filtered data into CSV format for offline use.

---

## 📊 Example Outputs

- Highlighted and styled data tables showing best stock picks.  
- Bar and scatter plots comparing financial metrics.  
- CSV file containing processed financial data.

---

## 🚀 Future Enhancements

- ✅ Integration with Machine Learning for stock prediction.  
- ✅ More advanced financial filters (Debt-to-Equity, EPS growth, etc.).  
- ✅ Real-time auto-updates and notifications.  
- ✅ Interactive dashboard (Plotly/Dash).  
- ✅ Mobile/web app interface for end users.

---

## 📁 Project Structure

```
Best-Stock-Buy/
│
├── BSB.ipynb               # Main Jupyter notebook with implementation
├── requirements.txt        # Project dependencies
├── README.md               # Project overview and documentation
├── LICENSE                 # Open-source license (MIT)
├── data/                   # (optional) Folder for CSV exports
├── visuals/                # (optional) Folder for charts or images
└── .gitignore              # Ignored files and folders
```

---

## 🧩 Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/vectorinfinity/Best-Stock-Buy.git
cd Best-Stock-Buy
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `BSB.ipynb` in **Jupyter Notebook** or **Google Colab**, and run all cells sequentially.

---

## 📜 License

This project is licensed under the terms of the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

- [Screener.in](https://www.screener.in) for stock data  
- [Python](https://www.python.org/), [pandas](https://pandas.pydata.org/), [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)  


---


