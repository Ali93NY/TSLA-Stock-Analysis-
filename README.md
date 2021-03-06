# TSLA-Stock-Analysis-
### Intro:
Tesla’s shares have been trading publicly since 2011 and many financial
analysts has forecasted for 6 to 9 years that this company would be on the verge of bankruptcy
for various reasons such as the difficulty of mass producing EVs, and the competition from EV
startups and other legacy automakers like General Motors and Ford. Lately,
many have realized they have been wrong on Tesla, as it has begun to disrupt the auto industry
and change the future of transportation. All of this has been reflected in Tesla’s share price
which has soared almost 800% since 2019. In this project, we will examine how Tesla’s stock
performance is in comparison to the overall market starting from 2019 up to Dec 2020 and how COVID 19
impacts the company share’s price. 

### Method:
Tesla’s share price data from to January 1st 2019 up to December 4th 2020 will be taken from Yahoo Finance. Correlation analysis and linear regression will be used to explore certain trends on TSLA stock in comparison to the overall market which will represented by SPY ETF which tracks the S&P 500 index and the QQQ ETF which tracks the the Nasdaq 100 index.  The correlation analysis will involve using rolling correlation across time to extract informative patterns of TSLA stock with the market. The linear regression will be used to compare TSLA linear trends before COVID-19 and after. It will also be utilized to quantify how TSLA share price varies as a function of SPY and QQQ by calculating the parameter Beta (𝛽) which is a coefficient that measures the volatility of a stock compared to the market as a whole.



### Results
TSLA , SPY and QQQ prices are shown in figure 1 from January 1st 2019 to December 4th 2020. The light yellow shaded region in figure 1 represents the period of COVID-19 impact on the US stock market from February 24th 2020 up to the last date in the graph. TSLA share price was suppressed in the first three quarters of 2019 in comparison to the overall market, but in the last quarter of 2019 the share price broke out and began an upward trend until COVID-19 reached the United States. TSLA share price plunged as the overall market due to COVID-19. However, the market and TSLA recovered around the month of April 2020 with TSLA taking
unprecedented upward trend and outperforming the market. What can also be seen from this figure is that TSLA is highly volatile with rapid upward and downward movements in comparison to the overall market especially during COVID-19 period.

![Figure 1](Fig1.png)

During the aforementioned period, Tesla stock price correlation with the SPY is 0.7 and with the QQQ is 0.94, but a single correlation number brings a limitation as the correlation of any stock to the market changes from time to time due to different and unpredictable factors. Therefore, a rolling correlation during the historical time period is more insightful than a single point estimate. Thus, figure 2 shows the 60 days rolling correlation between TSLA & SPY and TSLA & QQQ from the beginning of 2019 up to December 4th 2020. The figure shows that TSLA was negatively correlated with the market at the beginning of 2019. After June 2019 the stock has become positively correlated and the magnitude of the positive correlation was in an upward trend until COVID-19 hit the United States where the magnitude of the positive correlation decreased. However, Tesla’s share price became again strongly correlated with the stock market until the beginning of September 2020 where the magnitude of the positive correlation began to fluctuate.

![Figure 2](Fig2.png)

When comparing TSLA share price with the above 60 days rolling correlation visual, TSLA tends to break out when its correlation with the market drops, and the bottom of the 60 days rolling correlation drop represents a good buying opportunity as illustrated by the vertical dashed lines in figure 2. The same vertical dashed lines are drawn on figure 3 to show how good are the buying opportunities from the 60 days rolling correlation. From the four correlation based buying opportunities, TSLA moved up significantly at least 50 % on average. The first buying opportunity was on October 20th 2019 where TSLA 60 days rolling correlation with the market dropped to below 75%. After that, the stock started an upward trend, the price tripled from $60 in October 2019 to 180$ in February 2020. The second buying opportunity was on March 15th 2020 after COVID-19 hit the United States. The stock price bottomed at about $90 along with 60 days rolling correlation with the SPY which was below 25%. After that, TSLA surged upward for two months. The third buying opportunity was on July 17th 2020 where TSLA correlation dropped slightly with the market especially SPY. This buying opportunity lagged little bit for a few weeks, but the move was really explosive as TSLA moved approximately 84% in a very short period of time. The fourth buying opportunity was on November 4th 2020 as TSLA correlation started to drop from September 2020 until it bottomed at the beginning of November 2020. The TSLA move after this drop in the 60 days correlation is also explosive, as the stock increased approximately 50% in a short period from 400$ on November 16th 2020 to above 600$ on December 4th 2020.

![Figure 3](Fig3.png)

To know how TSLA share price varies as a function of SPY and QQQ, the daily returns of each share will be taken and regressed against each other. When TSLA regressed against SPY as shown in figure 3, the line of the best fit tells us that for every 1% increased return from the SPY, the expected TSLA’s return is 1.28 % and vice versa with R squared value of 0.21. When TSLA regressed against QQQ as shown in figure 4, the line of the best fit tells us that for every 1% increased return from the QQQ, the expected TSLA’s return is 1.37 % and vice versa with R squared value of 0.29. The expected TSLA return is known as the parameter Beta (𝛽) which is used to measure stock’s volatility in relation to the S&P 500 or other index like QQQ. A beta from 0 to 1 indicates a stock with low volatility, a beta of 1 indicates a stock with a similar volatility as the market and a beta greater than one indicates a volatile stock. Since TSLA’s beta measured by SPY and QQQ is greater than one in both cases, it’s proven quantitatively that Tesla’s share price is highly volatile as indicated visually from figure 1.

![Figure 4](Fig4.png)
![Figure 5](Fig5.png)

To clearly see how COVID-19 impacts Tesla’s share price, a linear regression line will be fitted
before and after COVID-19 as shown on figure 5. It is evident that there is a regime change on Tesla’s share price during COVID-19 era where the upward trend of the share price is accelerated which can be seen from COVID-19 era regression line (in green) in figure 3 in comparison to the pre COVID-19 regression line (in red). The whole set regression (yellow line) doesn’t capture the regime change caused by COVID-19, and the regression line is not predictive of the future data points. A regime change on the price movement generates a different underlying distribution, and splitting the data into two different parts results in a much better fit than a single regression line for the whole data set. According to Cathe Wood Ark invest CEO, one valid explanation for the rapid uptake on TSLA share price during COVID-19 is that innovative and disruptive technologies gain significant market share during difficult times similar to what happened to Zoom whose stock soared 700% due to COVID-19.

![Figure 6](Fig6.png)
