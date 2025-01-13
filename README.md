This project effectively combines several key techniques in algorithmic trading:
  1. Data Collection: Utilizes yfinance for fetching historical stock prices.
  2. Data Manipulation: Implements custom calculations for technical indicators like RSI.
  3. Trading Logic: Defines clear rules for executing trades based on market conditions.
  4. Portfolio Management: Tracks capital changes throughout the trading process.
  5. Data Visualization: Provides insights into trading performance through graphical representation.

![image](https://github.com/user-attachments/assets/32d24fe6-f02a-4a0e-b0c4-8b23400e9e0d)

Trading Logic
The program employs a set of trading rules based on RSI thresholds to determine when to buy, sell, short, or cover positions:
Trading Conditions:
Buy Condition: If the RSI falls below 35, a buy order is executed.
Sell Condition: If the RSI rises above 55 while holding a position, shares are sold.
Short Condition: If the RSI exceeds 75 and no position is held, a short position is initiated.
Cover Condition: If the RSI drops below 55 while holding a short position, it is covered.
