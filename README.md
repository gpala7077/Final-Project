# Forecasting_CryptoCurrency
Final Project
# Non-Technical Summary
Cryptocurrencies are a dynamic, rapidly evolving market. The most prevalent currency in the market, Bitcoin,
has grown in value from $327 in 2015 to $65,000 in 2021. This exponential growth has led to many different
speculations on how cryptocurrencies could be explained or modeled. We focused on Bitcoin, the most
prevalent and widely accepted coin. We explored multiple avenues for describing relationships between
Bitcoin and other financial instruments.
We began by analyzing the daily closing values of Bitcoin and then we investigated how it could relate to the
daily closing values of the traditional stock market, as well as with crypto-mining stocks and other
cryptocurrencies. We modeled Bitcoin on its own, as well as in models with the S&P 500 index, Ethereum,
Chainlink, Nvidia (NVDA), and Advanced Micro Devices (AMD).
We found that Bitcoin is more volatile than the traditional stocks in the dataset. There was no statistically
relevant relationship between Bitcoin and the S&P 500 or the graphics card manufacturer stocks. However,
there are relationships with Bitcoin and smaller cryptocurrencies like Ethereum and Chainlink that could
potentially be further exploited in a higher-frequency model. There was also a distinct shift in behavior over
the last year. We believe that a model focused on the prior year alone, or a higher frequency intra-day model,
may potentially have better performance.
Overall, we found that there were no exploitable relationships between bitcoin, the stock market, and cryptomining stocks. The most applicable model was only capable of forecasting the mean of the series instead of
being able to capture the true variance. In order to truly benefit there would need to be significant lag
correlation between the series.
For future work, we believe that higher frequency data may have more utility. Our analysis was limited to daily
values which appeared to only have spurious correlation. There might be a chance to find some significant
correlation if analyzing a more granular series such as hourly intervals or by minute intervals.
