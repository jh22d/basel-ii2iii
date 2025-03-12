# basel-ii2iii

Policy:  Tier 1 capital 4.5% -> 6% of RWA from Basel II to Basel III.

**current fe + did output**

------------------------------------------------------------------------------------
| Variable    | Coefficient | Std. Err. | t     | P>abs(t) | 90% Conf. Interval      |
|-------------|-------------|-----------|-------|------|---------------------------|
| TP          | -6.190274   | 3.132214  | -1.98 | 0.051 | -11.38607 to -0.9944814   |
| t1cr        | 0.6889748   | 0.3686563 | 1.87  | 0.064 | 0.0774388 to 1.300511     |
| gdp         | -0.0099364  | 0.0041104 | -2.42 | 0.017 | -0.0167548 to -0.003118   |
| cpi         | 1.811661    | 1.025921  | 1.77  | 0.080 | 0.1098385 to 3.513483     |
| stock_idx   | 0.0169595   | 0.0705168 | 0.24  | 0.810 | -0.1000154 to 0.1339345   |
| _cons       | 279.2408    | 121.7997  | 2.29  | 0.024 | 77.19644 to 481.2851      |
------------------------------------------------------------------------------------

** next step**
- add more variables on the bank level: CR (equity per asset), size/leverage ratio, EBITS (Earnings before interest and tax), RIR (real interest rate)
- collect data in 2011-2018 (beyond 2014Q1-2018Q1)
- cluster: D-SIB, G-SIB, smaller
