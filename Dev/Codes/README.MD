# Codes

-- This file stores the codes used to develop the trading strategy for Indian Markets. The exploration begins with a basic strategy of going long based on Volume, and Moving Averages.

### Objective:

To have a profitable short term trading strategy with below constrains (in Indian Stock Markets)

  1. Stocks will be selected from "NIFTY50", "NIFTYNEXT50" and "NIFTYMIDCAP100" list
  2. We can only go long on the stocks (i.e. only Buy stocks and can't short them for investment purpose)
  3. If more than one stock should be held, then each will have equal weight (in terms of % of money invested in each stock will be equal)
  4. There can be times when Portfolio has zero stock holdings (Though such period will give no returns, Investors can think of holding the money in overnight funds)
  5. When a buy signal appears, the buy price would be assumed as (High + Low)/2 for the next day
  6. When the stock has to be sold, it will be assumed that it is sold at (High + Low)/2 for the next day
  
