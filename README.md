# momentum

I want to test the momentum effect on different assets. I have daily price time series information for assets in the following asset classes:		

1	Equity Index			
2	Credit (Corporate Bonds)			
3	Govt Bond (Sovereign Bonds)			
4	Currencies			
5	Commodities			
6	Equity Factors			

I chose one of the above 6 asset classes, and I built momentum portfolios for each one of the assets in the chosen asset class.				
						
Step 1: starting from 12/31/2001, at each month-end time point, calculate the asset's return in the past 12 months, if the return is positive (negative), the portfolio longs (shorts) 100% of the asset and holds the long (short) position for the next month. 			

Step 2:	calculate the monthly returns for the above-built portfolio till 2020/8/31.			
