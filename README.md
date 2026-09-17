MT5 Expert Advisor: GBPUSDM15
Strategy logic:
The EA first searches the last 50 candles for a swing high and a swing low. 
A swing high is defined as a candle, which on the 5 candles prior, and the 5 candle after, has no part of the body or wick above the middle candle.
The EA sets a buy order and a sell order simultaneously at both swing points.
The order automatically expires after 50 hours if it isn't executed.
When price hits the order, it automatically risks 2% of the account, with a stop loss 15 points away.
When the trade is 2 points in profit, the stop loss automatically moves to break-even and trails 2 points away at all times.
Trade closes when price hits the original take profit of 50 points, or the trailing stop loss, or the initial stop loss 15 points away.
