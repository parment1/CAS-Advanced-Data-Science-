Abstract:

Pairs trading is a strategy in which a trader buys one asset while shorting another. The main premise of the trade is that when the two pairs diverge, they will likely converge again resulting in profit for the trader.

Pair Trading will work if you choose the right assets to form a pair. Clustering can help identifying stocks for a pair trade.

Research objective:

Find stocks to go long and short based on clusters and select the best methodology amongst the two followings:

-K means clustering
-Hierarchical clustering

Back-test the performance against based on Sharpe Ratio

Methodology:

- We use panda describe method to analyse our dataset. We see a wide in the raw data 
- We will transform the data by first calculate the return and volatility and then by scaling them using StandardScaler
- We use panda the elbow method to visualize the number of clusters. We cross-check with the silhouette method
- METHODOLOGY 1: K-Means clustering visualization
- METHODOLOGY 2: Hierarchical clustering - Dendrogram
- We take the spread between the long and the short legs and look at the performance based on the sharpe ratio

