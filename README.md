# NumbaOptimization


For the same dataframe (which in the example as stock data from three brazilian companies) we do the following operations:

- Get log return
- Get EWMA volatility
- Calculate two moving averages with different time windows 
- Create an indicator that shows which of the two time windows is greater for every period

We do the same operations again with a refactored code, used the Numba library, that optimizes python code.

The following results were seen:

Method processing time without using Numba: 0.04403567314147949 
Method processing time with Numba: 0.0009999275207519531 
Improvement of: 97.72927844763643%
