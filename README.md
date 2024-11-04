Excited to share my latest  project! This tool fetches real-time stock data and allows users to analyze trends using moving averages, MACD, RSI, and volatility—all visualized through an interactive interface powered by Streamlit. Here’s what I used to build it:

💻 Tech stack: Python, Pandas, Matplotlib, Streamlit, yFinance API
📊 Features:
• Moving Averages for trend analysis
• MACD & RSI for momentum tracking
• Volatility Analysis for market fluctuations

MACD (Moving Average Convergence Divergence)
Full Form: Moving Average Convergence Divergence

Explanation:
MACD is a trend-following momentum indicator that shows the relationship 
between two moving averages of a security's price. It’s often used to identify
potential buy and sell signals. The MACD is calculated by subtracting the 26-period
Exponential Moving Average (EMA) from the 12-period EMA.

MACD Line: This is the difference between the 12-day and 26-day EMAs.
Signal Line: A 9-day EMA of the MACD Line, used as a trigger for buy and sell signals.
Histogram: The difference between the MACD Line and the Signal Line, indicating the strength of the momentum.
Interpretation:

When the MACD crosses above the Signal Line, it may suggest a potential buy signal.
When the MACD crosses below the Signal Line, it may indicate a potential sell signal.
Larger histogram bars signify stronger momentum, either bullish or bearish.


 RSI (Relative Strength Index)
Full Form: Relative Strength Index

Explanation:
RSI is a momentum oscillator that measures the speed and change of price movements, oscillating between 0 and 100. It indicates whether a stock is overbought or oversold.

Formula: RSI = 100 - [100 / (1 + RS)], where RS is the average gain of up periods during a specific time frame (usually 14 days) divided by the average loss.
Interpretation:

Overbought (>70): When the RSI is above 70, it can indicate that a stock is overbought or overpriced, and a reversal or pullback could occur.
Oversold (<30): When the RSI is below 30, it suggests that the stock may be undervalued, which could mean a buying opportunity is near.
