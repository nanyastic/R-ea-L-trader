# R-ea-L-trader

Progress report so far-
a) Learnt how to use git bash and git hub to create repositories and collaborate 
b) Used online trading app to get a brief idea of how trading works in a real life setting;
this helped in learning technical financial terms like bull/bear market, sharpe ratio, cycilcal/directional investments etc
c) Did a bit of self reading on finance - Predictably Irrational by Dan Ariely
d) Did the prescribed reading up on reinforcement learning-
Markov decision processes- how they work, their parameters and basic equations
Discount factors and how they help get immediate/distant rewards
Bellman Equation for optimal cummulative rewards
Markov Reward processes 
Basic understadning of how agents act on environemnt and transition to states and get rewards 
Python for finance :
started off with basic python functions that i knew about
went on to commonly used pakcage numpy 
Pandas- data manipulation tool of python - used for fetching data samples(eg closing prices of apple stcok prices for a specified time period)
Resampling:
series.resample(freq) is a class called "DatetimeIndexResampler" which groups data in a Series object into regular time intervals. The argument "freq" determines the length of each interval.
series.resample.mean() is a complete statement that groups data into intervals, and then compute the mean of each interval. For example, if we want to aggregate the daily data into monthly data by mean:
data frames : comonly used data structure, essentially a table of different data types series objects kind of like a spreadsheet.
all resampling methods applied to panda series can also be applied to data frames
Linear Algebra:
Random variables and dsitributions, regression models and more mathematical tools
Capital Asset Pricing Model
Alpha and beta- a measure of market volaitlity; beta is a measure of how strongly a stock reacts to rise or decline in market 
If beta > 1 prices rise/fall more than market does => volaite beta= zero implies a market netural stock, i.e, changes in market dont affect that stock at all(inelastic)
Fama-French Three factor model :
R=α+βmMKT+βsSMB+βhHML
MKT is the excess return of the market. It's the value-weighted return of all CRSP firms incorporated in the US and listed on the NYSE, AMEX, or NASDAQ minus the 1-month Treasury Bill rate.
SMB (Small Minus Big) measures the excess return of stocks with small market cap over those with larger market cap.
HML (High Minus Low) measures the excess return of value stocks over growth stocks. Value stocks have high book to price ratio (B/P) than growth stocks.
Used to predict returns on NASDAQ
multi factor models are stock picking strategies
recommended to pick stocks by their value, quality (profitability) and momentum.
The empirically successful measure of value is book-to-price ratio (B/P), but other measures can be used simultaneously to form a more robust and reliable view of a stock's value.
5 measures to be used : book-to-price, earnings-to-price ratio (EPS), forecasted EPS, cash flow-to-enterprise value and sales-to-enterprise value. 
A few quality measures: total profit over assets, gross margin and free cash flow over assets. There are also various measures of momentum. 1-year momentum, fundamental momentum and returns around earnings announcement are good choices.
