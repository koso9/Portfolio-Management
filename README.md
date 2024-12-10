# **Portfolio Optimization Using Python: Maximizing Risk-Adjusted Returns**

## **Overview**
This project focuses on optimizing a stock portfolio to achieve the highest risk-adjusted return, measured by the Sharpe Ratio. By integrating live financial data from the `yfinance` API, the model uses Python to calculate optimal stock allocations based on historical performance and risk metrics.

---

## **Why It Matters**
In a world of volatile markets, effective portfolio optimization is critical for:
- **Investment Strategy**: Maximizing returns while managing risk.
- **Wealth Management**: Helping advisors and institutions create diversified portfolios.
- **Data-Driven Decisions**: Using historical and real-time data to back investment choices.

This project bridges **finance** and **technology**, showcasing skills applicable to roles in **quantitative analysis**, **data science**, and **financial consulting**.

---

## **Features**
### **1. Real-Time Financial Data**
- Fetches historical stock prices for a customizable portfolio of 40+ tickers.
- Handles data inconsistencies with forward-filling to ensure reliability.

### **2. Statistical Calculations**
- **Expected Return**: Uses annualized mean returns of portfolio components.
- **Risk (Volatility)**: Computes annualized portfolio standard deviation.
- **Sharpe Ratio**: Measures risk-adjusted performance.

### **3. Portfolio Optimization**
- Implements an efficient optimization algorithm to maximize the Sharpe Ratio.
- Constraints:
  - Allocations must sum to 100%.
  - No short positions allowed (weights between 0 and 1).

### **4. Results and Insights**
- Outputs optimal stock weights.
- Calculates expected portfolio return, volatility, and Sharpe Ratio.

---

## **Technology Stack**
- **Python**: Core programming language.
- **Libraries**:
  - `yfinance`: Fetches live financial data.
  - `numpy` and `pandas`: Handles numerical and tabular data.
  - `scipy.optimize`: Performs portfolio optimization.
- **API**: Integrates Yahoo Finance for historical stock data.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-optimization.git
   cd portfolio-optimization
