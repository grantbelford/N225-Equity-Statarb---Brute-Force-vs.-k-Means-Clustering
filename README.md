# N225 Equity Statarb Brute-Force (Industry) vs k-Means Clustering
Overview

Using 589 days of daily N225 constituent equity closing price data, we compare statarb peformance between: 
Strat 1/2. Statarb - Brute Force Method (ie. focus on Industry classifications) vs.
Strat 2/2. Statarb - k-Means Clustering

Process
1. In both cases,
2. The trading pairs are selected & sorted on a custom scoring system which combines both cointegration strength & correlation.
3. The top 5 highest-scoring pairs are selected for backtesting.

Outcome 
1. On an initial JPY 5,000,000 allocation to each strat,
2. We notice a modest improvement in aggregate portfolio return from Strat2 (0.50%) vs. Strat1 (-1.1%).
 
