### By Vinay Kakuru

## Performance Analysis


 - Q. Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?

- **A. Yes, ALGO_1 and Berkshire Hathaway outperform S&P 500**

- Q. Calculate the cumulative terms by month and year. What were the best returns in 2017? What were the best returns for December 2018?

- **A. Best returns in 2017 was Berkshire Hathaway; Best returns in December 2018 was ALGO_1**

## Risk Analysis


- Q. Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?

- **A. Tiger Global has the largest spread. Paulson & Co. has the smallest spread.**

- Q. Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?

- **A. Tiger GLobal and Berkshire Hathaway are riskier than S&P 500**



## Rolling Statistics


- Q. Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does risk increase for each of the portfolios at the same time risk increases in the S&P?
Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?

- **A. Yes, the risk for the portfolios increase with S&P 500. ALGO_2 has the highest correlation with S&P 500 at 0.858764**


- Q. Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?

- **A. For Berkshire Hathaway is sensitive to S&P 500. The sensitivity gets worse starting 2016 based on a 21 day rolling Beta.**

## Plot Sharpe Ratios

 - Q. Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. (After all, if you have two portfolios that each offer a 10% return, yet one is lower risk, you would invest in the lower-risk portfolio, right?)

- **A. Yes, higher sharp ratio portfolio have lower risk associated**

- Q. Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.
Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.

- **A. ALGO_1 outperforms S&P 500 and other portfolios. ALGO_2 outperforms most portfolios except when compared to ALGO_1, S&P 500 and Berkshire Hathaway**


## Create Custom Portfolio

Harold is ecstatic that you were able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales portfolios. However, now you are wondering whether you can choose your own portfolio that performs just as well as the algorithmic portfolios. Investigate by doing the following:


Visit NASDAQ's Historical Price Data and choose 3-5 stocks for your own portfolio.
Download the data as CSV files and calculate the portfolio returns.

- Q. Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?

- **A. Custom portfolio has the second highest sharpe ratio after ALGO_1, providing good returns for the level of risk taken.**