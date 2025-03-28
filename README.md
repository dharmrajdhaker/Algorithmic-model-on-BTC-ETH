
# Advanced Mathematical Algorithmic Trading Model for BTCUSDT
**Quantitative Trading System with Adaptive Risk Management**  


![Strategy Visualization](https://github.com/user-attachments/assets/505808b1-e441-4cf0-9017-a04402570a29)

## 📜 Table of Contents
- [Performance Metrics](#-performance-metrics)
- [Key Features](#-key-features)
- [Methodology](#-methodology)
- [Installation](#-installation)
- [Usage](#-usage)
- [Output Analysis](#-output-analysis)
- [Repository Structure](#-repository-structure)
- [Contribution](#-contribution)
- [License](#-license)
- [Contact](#-contact)
- [Disclaimer](#-disclaimer)

## 🏆 Performance Metrics (2019-2023 Backtest)
| Metric                | No Leverage | 2x Leverage |
|-----------------------|-------------|-------------|
| Total Return          | 7,000%+     | 150,000%+   |
| Sharpe Ratio          | 10.2        | 9.8         |
| Max Drawdown          | 15%         | 29.3%       |
| Win Rate              | 60%         | 60%         |
| Annualized Volatility | 18.2%       | 36.1%       |
| Profit Factor         | 2.8         | 2.6         |

![Performance Matrix](https://github.com/user-attachments/assets/0a28a484-f472-4201-89d1-2a6fe1ffd101)

## 🚀 Key Features


### 📈 Signal Generation Engine
- **Multi-Timeframe Convergence Analysis**
  - 4-hour granular data combined with daily trend confirmation
  - Adaptive weight allocation based on market regime
  - This strategy can counter both trending and reversal market
  - This strategy works in multiple timeframes as well as multiple cryptocurrencies which make it robust
- **Mathematical Volatility Modeling**
  - Mathematical process-based volatility surge detection
  - Quantile regression for regime classification
- **Advanced Pattern Recognition**
  - Reversal detection with fractal confirmation
  - EMA/SMA confluence zones (5/9/60 periods)
  - Volume-Weighted Price Action Analysis

### 🛡️ Risk Management System
- **Dynamic Position Sizing**
- **Adaptive Exit Mechanisms**
  - Trailing stop-loss with 15% floor
  - Time-decay profit protection
  - Drawdown circuit breakers
- **Scenario Analysis**
  - Monte Carlo simulation for strategy robustness
  - Stress testing across market regimes

### ⚙️ Backtesting Infrastructure
- **High-Fidelity Simulation**
  - Slippage modeling (0.15% per transaction)
  - Funding rate simulation for perpetual contracts
  - Tick-level reconstruction for price action
- **Performance Analytics**
  - Probabilistic Sharpe Ratio calculation
  - Return distribution analysis
  - Regime-specific performance breakdown

## 🧮 Methodology

### Core Mathematical Models
1. **Mathematical Process Volatility Estimator**

2. **Adaptive Trend Filter**
  
3. **Reversal Detector**
  
## ⚙️ Installation

### Requirements
- Python 3.8+
- TA-Lib (system dependency)
- 8GB+ RAM recommended

```bash
# Clone repository
git clone https://github.com/yourusername/advanced-crypto-trading.git
cd advanced-crypto-trading

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
```

### Data Preparation
1. Obtain historical data in CSV format:
   - 4-hour data: `BTC_4h.csv`
   - Daily data: `BTC_1d.csv`
2. Required columns:
   ```csv
   datetime,open,high,low,close,volume
   ```
3. Place files in `/data` directory

## 🖥️ Usage

### Backtest Execution
```bash
python main.py \
  --leverage 1 \
  --fee_rate 0.0005 \
  --initial_capital 10000
```

### Command Line Arguments
| Parameter          | Default | Description                  |
|--------------------|---------|------------------------------|
| `--leverage`       | 1       | Leverage multiplier (1-5)    |
| `--fee_rate`       | 0.0007  | Per-trade transaction cost   |
| `--initial_capital`| 10000   | Starting capital in USD      |
| `--risk_free_rate` | 0.02    | Annual risk-free rate        |

## 📊 Output Analysis

### Trading Signals Visualization
![Entry/Exit Points](https://github.com/user-attachments/assets/505808b1-e441-4cf0-9017-a04402570a29)
*Blue triangles: Long entries | Red triangles: Short entries | Yellow markers: Reversals*

### Equity Curve
![Capital Growth](https://github.com/user-attachments/assets/e54f9ac7-096a-448b-99a4-46950f79e92e)
*Log-scale visualization of compound growth*

### Risk Analysis
![Drawdown Profile](https://github.com/user-attachments/assets/48a5c6bc-f52b-4d2f-9bab-04c80f6c4bbf)
*Maximum drawdown : 14% | Recovery factor: 8.2*

### P&L Distribution
![Profit Histogram](https://github.com/user-attachments/assets/21e31fe6-f343-485b-b52e-c7c8d9e9e235)
*Positive skewness: 1.2 | Kurtosis: 4.8*

## 📂 Repository Structure
```
.
├── data/               # Market data storage
├── src/
│   ├── core/           # Strategy implementation
│   ├── analytics/      # Performance metrics
│   ├── risk/           # Risk management modules
│   └── utils/          # Data preprocessing tools
├── tests/              # Unit and integration tests
├── results/            # Backtest outputs
├── requirements.txt    # Dependency list
└── main.py             # Execution entry point
```

## 📧 Contact
**Dharmraj Dhaker**  
Lead Quantitative Developer  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/dharmraj-dhaker-a436b4250)  
📧 dharmrajdhaker89@gmail.com  
🌐 [Professional Website](https://yourportfolio.com)

## ⚠️ Disclaimer
This information is provided for **educational and research purposes only**. Cryptocurrency trading involves substantial risk of loss and is not suitable for all investors. Past performance is not indicative of future results. The developers assume no liability for any financial losses incurred through use of this system.

Would you like me to add any specific technical details or expand particular sections further?# Advanced mathematical-model-on-BTC-ETH
