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
1. On an initial JPY 5m allocation to each strat (ie. JPY 1m per pair),
2. We notice a modest improvement in aggregate portfolio return from Strat2 (0.50%) vs. Strat1 (-1.1%).
3. 1 pair (2768.T Sojitz Corp vs. 8053.T Sumitomo Corp overlapped on both strats top 5 picks. Strat1 grouped the pair because both are in Conglomerates industry & Strat2 grouped the pair based on high return correlation. Both Sojitz and Sumitomo are sogo shosha (general trading companies) which could explain their similar return pattern.
 
