This repo includes two long-short-term memory networks, a uni-directional and bi-directional. Inspired by this paper: https://www.mdpi.com/2504-3110/7/2/203.

The HistoricalData.py script is a script originally from this library: https://pypi.org/project/Historic-Crypto/ but I have made slight alterrations to get it
to work for my use case. 

The model(s) predictions are dependent on the temporal structure of the data, the Historicaldata.py script allows for granularity in time to be adjusted based on seconds 
(the default for this use case is 21600 seconds, measured every 6 hours beginning at 6am). The ultimate goal is to wrap this model in a high frequency trading algorithm. 
