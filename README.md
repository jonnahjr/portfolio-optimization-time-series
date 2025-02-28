# 📈 Time Series Forecasting for Portfolio Management Optimization

This repository provides a solution for time series forecasting of financial assets using **ARIMA, SARIMA, and LSTM** models. The goal is to **predict market trends 📊 and optimize portfolio performance 💰** for **GMF Investments**, improving **decision-making** and **risk management**.

---

## 📌 Business Need
GMF Investments aims to enhance **portfolio management** by leveraging **predictive analytics 🤖**, optimizing **asset allocations**, and minimizing **risks ⚠️** through accurate **market forecasting**.

---

## 🎯 Objective
✅ **Data Preprocessing**: Clean and analyze **historical financial data** from assets like **TSLA, BND, and SPY**.
✅ **Time Series Forecasting**: Implement **ARIMA, SARIMA, and LSTM** models for market trend prediction.
✅ **Portfolio Optimization**: Use forecasts to **adjust portfolio allocations** for better **returns 📈 and risk management**.

---

## 📊 Data
We use **historical financial data** for three key assets:
- **📌 Tesla (TSLA)**: Stock prices (**Open, High, Low, Close**), **Volume**, and **Volatility**.
- **📌 Vanguard Total Bond Market ETF (BND)**.
- **📌 S&P 500 ETF (SPY)**.

📅 **Data Source**: [YFinance](https://pypi.org/project/yfinance/)
📆 **Time Period**: January 1, 2015 - December 31, 2024

---

## ⚙️ Setup
### 1️⃣ Clone the Repository
```bash
 git clone https://github.com/jonnahjr/portfolio-optimization-time-series.git
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Navigate to Scripts Directory
```bash
cd scripts
```

### 4️⃣ Run the Main Script
```bash
python main.py
```

---

## 📂 Project Structure
📂 project/
├── 📁 data/                      # Raw and processed data for analysis
├── 📁 models/                    # Forecasting models (ARIMA, SARIMA, LSTM)
├── 📁 notebooks/                 # Jupyter notebooks for EDA, model implementation, and optimization results
├── 📁 requirements.txt           # Lists required Python packages
├── 📁 scripts/                   # Executable scripts, including main.py
├── 📁 tests/                     # Unit tests to ensure code functionality and reliability
├── 📁 src/                       # Core source files for model training and evaluation
├── 📁 Dockerfile/                # Defines the Docker environment for deployment
├── 📁 .github/
│   └── 📁 workflows/             # GitHub Actions CI/CD pipeline
└── 📁 figures/                   # Images and plots generated during analysis


---

## 📞 Contact Information
👤 **Name**: Yonas Bogale Sitotaw  
🐙 **GitHub**: [jonnahjr](https://github.com/jonnahjr)  
📧 **Email**: [jonnahjr@gmail.com](mailto:jonnahjr@gmail.com)  
🔗 **LinkedIn**: [jonnahjr](https://www.linkedin.com/in/jonnahjr)  

---

## ⚖️ License
This project is **licensed under the MIT License** - see the [LICENSE](LICENSE) file for details.

🚀 Happy Coding! 🎯
