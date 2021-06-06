# TSLA-Stock-Analysis-
### Intro:
Tesla’s shares have been trading publicly since 2011 and many financial
analysts has forecasted for 6 to 9 years that this company would be on the verge of bankruptcy
for various reasons such as the difficulty of mass producing EVs, and the competition from EV
startups and other legacy automakers like General Motors and Ford. Lately,
many have realized they have been wrong on Tesla, as it has begun to disrupt the auto industry
and change the future of transportation. All of this has been reflected in Tesla’s share price
which has soared almost 800% since last year. In this project, we will examine how Tesla’s stock
performance is in comparison to the overall market starting from 2019 up to Dec 2020 and how COVID 19
impacts the company share’s price. We will investigate what kinds of statistical models could
forecast the short term movements of the stock with buying and selling signals.

### Method:
Tesla’s share price data from to January 1st 2019 up to December 4th 2020 will be taken from Yahoo Finance. Correlation analysis and linear regression will be used to explore certain trends on TSLA stock in comparison to the overall market. The correlation analysis will involve using rolling correlation across time to extract informative patterns of TSLA stock with the market. The linear regression will be used to compare TSLA linear trends before COVID-19 and after. It will also be utilized to quantify how TSLA share price varies as a function of SPY and QQQ by calculating the parameter Beta (𝛽) which is a coefficient that measures the volatility of a stock compared to the market as whole.

The Autoregressive Integrated Moving Average ARIMA (p,d,q) will be used to forecast the short term TSLA returns. The Generalized Autoregressive Conditional Heteroskedasticity GARCH (p, q) model will be used to forecast the short term volatility of TSLA stock price. 

