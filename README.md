Task : Calculate Trend Score for tick wise data of Commodity Prices.

-> A score between 0 and 1 formulated as `(Price - Minima)/(Maxima - Minima)` for that sub product.

-> If the current price increased from the prev. timestamp → keep the Trend Score.

-> If it decreased → multiply by 0.5.
