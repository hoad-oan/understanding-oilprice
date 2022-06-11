# understanding-oilprice

With the current situation regarding the unstable prices of oil and future uncertainty, I have this project to better understand what drives oil prices in the U.S. and what factors can be used to predict them. Data was collected from the beginning of COVID till now and was broken into 2 timeline: when COVID was heavy in the U.S. and when COVID was more under controlled in the U.S. This is to address confounding problem that is the pandemic.

Included in this python Notebook:
1. Pulling data from Twitter and NewsCatcher API, aggregating data and performing sentiment analysis (NLTK library), emotions analysis (IBM’s Watson Emotion Detection library), and time series analysis (Granger Causality) with oil prices
2. Pulling stock market popular indices such as S&P500 and Fear Index to find correlations and perform time series analysis (Granger Causality) with oil prices

