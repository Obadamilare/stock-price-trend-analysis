# Stock Price Trend Analysis

A quantitative financial simulation built with core Python fundamentals to track performance metrics, compare target thresholds, and analyze stock price trends.

## Project Overview

In the global FinTech and investment landscape, automated decision-making engines calculate thousands of market metrics per second to guide investment strategies. 

This project simulates core logic behind modern financial platforms (such as Bamboo, Trove, and Robinhood) by analyzing historical or simulated asset prices, calculating daily returns/price deltas, and evaluating trend direction using fundamental programming logic.

## Key Objectives & Capabilities

- **Price Movement Tracking:** Evaluate day-over-day price differences to identify upward or downward trends.
- **Metric Calculations:** Compute key trading metrics such as profit margins, price variance, and performance percentages.
- **Threshold & Signal Analysis:** Compare current asset prices against target thresholds to identify potential buying/selling signals.
- **Structured Logic:** Implement clean conditional evaluation using standard Python operators (Arithmetic, Comparison, and Logical operators).


##  Mathematical & Quantitative Foundation

As a Mathematics student and Quantitative Analyst in training, I approach financial problems by translating market behaviors into structured mathematical logic:

1. **Price Delta ($\Delta P$):**
   $$\Delta P = P_{\text{current}} - P_{\text{previous}}$$

2. **Percentage Return ($R$):**
   $$R = \left( \frac{P_{\text{current}} - P_{\text{previous}}}{P_{\text{previous}}} \right) \times 100$$

3. **Trend Classification Logic:**
   $$\text{Trend} = \begin{cases} \text{Bullish (Upward)}, & \text{if } \Delta P > 0 \\ \text{Bearish (Downward)}, & \text{if } \Delta P < 0 \\ \text{Neutral}, & \text{if } \Delta P = 0 \end{cases}$$


## Tech Stack & Tools

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook / VS Code
- **Core Concepts Used:** Variables, Data Types, Arithmetic & Logical Operators, Comparison Operators, Conditional Statements.

## Notebook Execution & Visual Results

Below are screenshots from the interactive **Jupyter Notebook** showcasing the code execution and output:

### 1. Script Execution & Output
*The console output demonstrating automated stock trend evaluations and calculations:*

![Execution Output 1](./Screenshot%202026-07-23%20132357.png)
![Execution Output 2](./Screenshot%202026-07-23%20132414.png)
![Execution Output 3](./Screenshot%202026-07-23%20132427.png)
![Execution Output 4](./Screenshot%202026-07-23%20132446.png)
![Execution Output 5](./Screenshot%202026-07-23%20132534.png)

## Key Quantitative Findings & Insights

Based on the simulated execution across NovaTech Plc (NVT) and GreenEnergy Ltd (GEL):

- **Target Achievement:** NovaTech Plc successfully hit its target price threshold (reaching ₦172.00 vs ₦170.00 target), while GreenEnergy Ltd fell short of its target.
- **Growth Expectations:** NovaTech exceeded expected daily growth (10% actual vs 8% expected), whereas GreenEnergy underperformed (4% actual vs 5% expected).
- **Advisor Action Signals:** Boolean rule evaluation flagged GreenEnergy Ltd as requiring financial advisor attention due to underperformance relative to investor growth expectations.


##  Future Enhancements

To upgrade this model into an enterprise grade Quantitative Finance tool, the following features will be integrated in upcoming releases:

1. **Live Data Integration:** Connect to real-time market data APIs (YFinance, Alpha Vantage, or Bloomberg API) to stream live order book data instead of static variables.
2. **Statistical Risk Metrics:** Implement Volatility calculations, Sharpe Ratio, and Maximum Drawdown (MDD) tracking to evaluate risk-adjusted returns.
3. **Automated Trading Signals:** Develop algorithmic trade triggers (e.g., Simple Moving Average crossovers and Bollinger Bands) using vectorized Pandas operations.
4. **Interactive Dashboard:** Build a Web UI frontend using Streamlit or Dash to visualize live price movements and execution reports.


## Author

**Adekogbon Obadamilare Testimony (Wīsdøm)**
*Undergraduate Student in Mathematics | Student Tutor & Aspiring Quantitative Analyst*
