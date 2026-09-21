# 📈 Iran GDP Macro-Economic Technical Analyzer (1978 - 2025)
  Macroeconomic Time-Series Analysis of Iran GDP Growth (1978-2025) using Financial Technical Indicators (Ichimoku, RSI, MACD, Bollinger, Stochastic) built with PyQt5 &amp; PyQtGraph.


An experimental and advanced Desktop GUI application built with **Python 3.9**, **PyQt5**, and **PyQtGraph** that applies financial market technical indicators to macro-economic time series data (Iran Annual Real GDP Growth Rate from the World Bank dataset).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![UI: PyQt5](https://img.shields.io/badge/GUI-PyQt5%20%7C%20PyQtGraph-green.svg)](https://riverbankcomputing.com/software/pyqt/)

---

** 🚀 Key Features: **

- Macro Dataset:** Official World Bank Historical & Forecast GDP Growth Data for Iran (1978–2025).
- **Technical Indicators Applied to Macro Data:**
  - **Ichimoku Kinko Hyo (5 Elements):** Tenkan-sen (9), Kijun-sen (26), Senkou Span A/B (+26 projected cloud), Chikou Span (-26).
  - **Bollinger Bands:** (20, 2σ) volatility bands.
  - **Relative Strength Index (RSI):** 14-period momentum oscillator with dynamic overbought/oversold levels.
  - **Stochastic Oscillator:** Fast/Slow (%K 14, %D 3).
  - **MACD Subplot:** (12, 26, 9) exponential moving averages + dynamic color histogram.
- **Data Persistence:** SQLite embedded database with Live Sync, Save, Load, and Factory Reset.
- **Reporting & Export:** Interactive HTML/PDF styled reports & Excel (.xlsx/.csv) export.
- **Themes & Zoom:** 5 distinct themes (`Drk`, `Clsc`, `Pro`, `Org`, `Pnk`) with responsive font scaling.

---

 🛠️ Installation & Setup

1. Clone the repository:
```bash
   git clone https://github.com/parvizt/iran-gdp-technical-analyzer.git
   cd iran-gdp-technical-analyzer


2. Create a virtual environment (Recommended):
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On Linux/macOS:
   source venv/bin/activate

3. Install dependencies:
   pip install -r requirements.txt
   
4. Run the Application:
   python main.py
Default Admin Password: admin
   
5. 📊 Data Source:
Primary Source: World Bank Open Data (WDI indicator: NY.GDP.MKTP.KD.ZG - Iran, Islamic Rep. GDP growth annual %).
Range: 1978 to 2025.

6. 👨‍💻 Author & Attribution:
Developer: Parviz Tajdari (james919)
Brand / Organization: AiBrothersTools.ir
Freelance Profile: kwork.com/user/parvizt

7. 📄 License: 
Distributed under the MIT License. See LICENSE for more information.






   
