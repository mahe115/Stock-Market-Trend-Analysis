# Stock-Market-Trend-Analysis
The dataset contains the following columns:

- Date
- Open: Opening price of the stock on that day
- High: Highest price of the stock on that day
- Low: Lowest price of the stock on that day
- Close(t): Closing price of the stock on that day
- Adj Close: Adjusted closing price, accounting for distributions and corporate actions
- Volume: Number of shares traded on that day
- day: Day of the month
- month: Month of the year
- year: Year
- quarter: Quarter of the year

# exploratory analysis to identify 10 key investment patterns and insights over the period from June 29, 2010, to March 17, 2017.

**Summary Of Tesla's Stocks**
![Trend Analysis Over Time](https://github.com/mahe115/Stock-Market-Trend-Analysis/blob/main/Tesla/data%20visualiztion/Screenshot%20(161).png)
Findings from the exploratory analysis:

1. **Trend Analysis Over Time**:
   
  ![Trend Analysis Over Time](https://github.com/mahe115/Stock-Market-Trend-Analysis/blob/main/Tesla/data%20visualiztion/Screenshot%20(164).png)
   - Both the closing price and the adjusted closing price show a general upward trend from 2010 to 2017, indicating a long-term growth in Tesla's stock value.

2. **Volume Analysis**:
   - Trading volume exhibits significant fluctuations. Peaks in volume often align with major stock price movements, suggesting that high trading activity is associated with price volatility.

3. **Monthly and Quarterly Patterns**:
   - Monthly and quarterly aggregation of closing prices reveal consistent upward trends, with some periods of stabilization or slight decline. Quarterly data smooths out the short-term volatility observed in monthly data.



5. **Price Movement Correlation**:
   - The correlation matrix indicates a very high correlation between opening, high, low, closing, and adjusted closing prices, all close to 1. This suggests that these prices move together closely on a day-to-day basis.

6. **Adjusted Close Discrepancies**:
   - Discrepancies between the adjusted close price and the next day's opening price occur periodically, indicating potential market reactions to after-hours news or corporate actions.

7. **High-Low Spread**:
   - The spread between the daily high and low prices varies significantly, reflecting intraday volatility. Periods of larger spreads align with increased trading activity and price fluctuations.

8. **Volume-Price Correlation**:
   - The correlation between trading volume and daily price changes is 0.075, suggesting a weak positive relationship. This indicates that higher trading volumes are slightly associated with larger price changes but not strongly.

9. **Impact of Corporate Actions**:
   - While specific corporate actions are not listed, the discrepancies identified earlier and periods of high volatility can hint at corporate events such as earnings reports, stock splits, or other significant announcements.

10. **Seasonal Effects**:
    - An analysis of average monthly closing prices reveals some seasonal patterns. For example, certain months like May and September exhibit relatively higher average closing prices, potentially due to market or company-specific factors.

### Summary of Key Investment Patterns and Insights

1. **Long-term Upward Trend**: Tesla's stock price has shown a general upward trend from 2010 to 2017.
2. **Volume Peaks and Volatility**: High trading volumes often coincide with significant price movements.
3. **Monthly and Quarterly Trends**: Consistent growth patterns with some stabilization periods.
4. **Volatility Periods**: Notable periods of high volatility around 2013 and 2015.
5. **Price Correlations**: High correlation between opening, high, low, closing, and adjusted closing prices.
6. **Adjusted Close Discrepancies**: Periodic discrepancies between adjusted close and next day’s opening prices.
7. **Intraday Volatility**: Significant variation in the high-low spread, indicating intraday price volatility.
8. **Weak Volume-Price Correlation**: A weak positive correlation between trading volume and price changes.
9. **Potential Corporate Impact**: Major discrepancies and volatility may align with corporate actions or news.
10. **Seasonal Patterns**: Some months exhibit higher average closing prices, suggesting seasonal effects.

These insights can help investors understand Tesla's stock behavior and make more informed investment decisions.
