Sales_TopN_RankX_POC.pbix
Rank Sales = RANKX(	ALL('Sales'[Product])	, CALCULATE(SUM('Sales'[SalesAmount]))	, 	, DESC	, Dense)
