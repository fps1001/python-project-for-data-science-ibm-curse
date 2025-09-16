# Python Project for Data Science (IBM — Coursera)

This repository contains the code for the *Analyzing Historical Stock Revenue Data and Building a Dashboard* project in the **Python Project for Data Science** course on Coursera by IBM.

Fernando Pisot Serrano
---

## 🧭 Project Overview

- **Course:** Python Project for Data Science (IBM, Coursera)  
- **Lab / Assignment:** Hands‑on Lab — Analyzing historical stock & revenue data and building a dashboard  
- **Objective:**  
  1. Obtain historical stock data for a company (e.g. Tesla, GameStop etc.)  
  2. Scrape or load revenue data for the same company  
  3. Clean and merge those datasets  
  4. Create visualizations / build a dashboard to analyze revenue vs stock trends  

---

## 📁 Repository Structure

| File / Folder | Description |
|----------------|-------------|
| `Final Assignment‑v2.ipynb` | Jupyter Notebook containing the assignment: data extraction, cleaning, analysis, and visualizations. |
| `Question1.png` | Example or template image showing the expected output / plot for Question 1. |
| `Question2.png` | Expected output / plot for Question 2. |
| `Question3.png` | Expected output / plot for Question 3. |

---

## 🛠 Technical Details

- **Language / Environment**: Python (Jupyter Notebook)  
- **Libraries used** (common ones, you may add more): `pandas`, `numpy`, `requests` / `BeautifulSoup` (or an equivalent for scraping), `matplotlib` or `plotly` / `seaborn` for plotting.  
- **Data Sources**:  
  - Historical stock prices via an API or package (e.g. Yahoo Finance, or another financial data provider)  
  - Revenue data either scraped from the web or loaded from a data file  

---

## 🚀 How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/fps1001/python-project-for-data-science-ibm-curse.git
   cd python-project-for-data-science-ibm-curse
   ```

2. Create and activate a Python virtual environment (optional but recommended):

   ```bash
   python3 ‑m venv venv
   source venv/bin/activate   # On macOS / Linux
   # or
   venv\Scripts\activate      # On Windows
   ```

3. Install required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn requests beautifulsoup4 plotly
   ```

   *(Adjust list to match what's actually used in your notebook.)*

4. Open and run the notebook:

   ```bash
   jupyter notebook Final\ Assignment‑v2.ipynb
   ```

   or using JupyterLab / VSCode as preferred.

5. Follow through the notebook: fetching data, cleaning, visualizing, and compare your results with the expected plots (`Question1.png`, etc.).

---

## ✅ What’s Completed / To Do

| Task | Status |
|------|--------|
| Fetch historical stock data | ✔ Completed |
| Fetch revenue data | ✔ Completed |
| Data cleaning / formatting | ✔ Completed |
| Merge datasets (stock + revenue) | ✔ Completed |
| Visualization: stock price trends | ✔ Completed |
| Visualization: revenue trends | ✔ Completed |
| Dashboard (combining both) | In progress or Completed depending on your version |
| Compare results with expected / checks | To verify |

---

## 💡 Tips & Good Practices

- Check for missing data or gaps in dates (for example, weekends/holidays for stock data).  
- Ensure the revenue data and stock price data are aligned by date (or as close as possible).  
- Use plots that clearly show both revenue and stock metrics; think about dual‑axis plots or subplots.  
- Add appropriate labels, titles, legends, and formatting for readability.  
- If scraping, handle errors and consider caching data to avoid repeated HTTP requests.  

---

## 📚 References

- IBM / Coursera course materials  
- Documentation for libraries used (Pandas, Matplotlib / Plotly, etc.)  
- If scraping: documentation for HTTP requests / BeautifulSoup or other tools used  

---

## 📝 License

This project is for educational purposes only, as part of the Coursera course. Feel free to use it for your learning, but do **not** distribute it as your own if submitting similar work for assessment.
