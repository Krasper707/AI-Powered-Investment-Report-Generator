# AI-Powered Investment Report Generator

## 📌 Overview
The **AI-Powered Investment Report Generator** is a cutting-edge financial analytics tool that automates the generation of investment reports using **LangChain**, **NLP**, and **historical stock data**. The tool leverages data from **Yahoo Finance**, **Alpha Vantage**, and **yfinance** to provide insightful financial analysis, comparative historical trends, and AI-driven stock rankings.

## 🚀 Features
- **Automated Markdown Reports**: Generates investment reports in Markdown format.
- **Financial Data Extraction**: Fetches key stock metrics, including P/E Ratio, EPS, Dividend Yield, and Revenue Growth.
- **Historical Comparisons**: Analyzes historical stock performance against current trends.
- **AI-Based Stock Ranking**: Uses a weighted scoring system to rank stocks.
- **Charts & Visualizations**: Generates financial charts for data-driven insights.
- **Multi-Stock Comparison**: Compares multiple stocks for investment decisions.
- **Inline Base64 Image Embedding**: Ensures portability of reports with embedded charts.
- **Modular API Support**: Easily extendable to support additional financial APIs.

## 📊 Data Sources
- **Yahoo Finance API** (Current and historical stock data)
- **Alpha Vantage API** (Fundamental stock data)

## 🛠️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/investment-report-generator.git
cd investment-report-generator

# Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🔑 API Configuration
Before running the tool, set up your API keys in a `.env` file:

```ini
# .env file
ALPHA_VANTAGE_API_KEY=your_alpha_vantage_key
YAHOO_FINANCE_API_KEY=your_yahoo_finance_key
GENAI_API_KEY=your_genai_key
```

## 🔧 Usage
```python
from report_generator import generate_investment_report

ticker = "AAPL"  # Example stock ticker
report = generate_investment_report(ticker)
print(report)  # Outputs Markdown formatted report
```

### 📈 Chart Generation
Charts are generated dynamically using **Matplotlib** and are embedded as **Base64 images** within the Markdown reports. These charts provide:
- P/E Ratio Trends
- Revenue Growth Analysis
- Dividend Sustainability Insights

## 🔮 Future Enhancements
- **Real-time data integration** for up-to-date financial insights.
- **News sentiment analysis** to assess market sentiment.
- **Reddit and social media trend analysis** for investment signals.
- **Advanced AI-driven ranking models**.
- **Portfolio Optimization Suggestions** using ML-based models.

## 🌐 Web Application (Upcoming)
The project is evolving into a full-fledged **Web App** that will:
- Provide an **interactive dashboard** for stock analysis.
- Support **real-time data streaming** for stock price monitoring.
- Allow users to **customize financial reports** based on selected metrics.

## 🤝 Contributions
Contributions are welcome! Feel free to submit issues or pull requests to enhance the tool.

## 🛡️ License
This project is licensed under the **MIT License**.

