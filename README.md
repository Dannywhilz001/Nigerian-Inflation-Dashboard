# Nigerian Inflation Dashboard (2003 – Oct 2025)

[Nigeria Inflation Dashboard 1](https://ibb.co/v60NNJmQ)
[Nigeria Inflation Dashboard 2](https://ibb.co/0yW5bw1h)

*22+ years of official CBN inflation data — cleaned, visualized, and ready to use.*

### What you’ll find here
- Raw CBN Excel file (data raw/Inflation_Data_in_Excel.xlsx)
- Fully cleaned dataset with proper datetime index
- Publication-ready chart showing:
  - Headline Inflation (All Items YoY)
  - Food Inflation (YoY)
  - Core Inflation (All Items less Farm Produce)

### Key Insights from the Data
- Food inflation has repeatedly been the dominant driver of headline inflation
- Core inflation (ex-farm produce) remains sticky even when food prices cool
- Peak headline inflation hit ~34% in mid-2024

### How to Run
```bash
git clone https://github.com/Dannywhilz001/Nigerian-Inflation-Dashboard.git
cd Nigerian-Inflation-Dashboard
pip install -r requirements.txt
jupyter notebook "Nigerian_Inflation_Dashboard.ipynb"
