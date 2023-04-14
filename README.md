# Influential-Analysis-of-LastFM

#About The Project
The repo gives an overview on how to do Influential Analysis. Basically, It focuses on how to fetch Data from Last FM and make analysis on the fetched data. We highly recommend you to read the script fully with comments to understand the flow better.

#Data Fetching
We certainly have to obtain the api key for Last FM and have to use only provided user "rj" to fetch the data.

#Threshold
To determine the threshold we have to specify the unix timestamp for the desired time interval. Here we have done for 4 months Jan 2021 - April 2021.

#EdgeWeight
We have to then find the edge weight of each interaction based on the threshold decided. 

#Analysis
1. Direct Influence(BFS) - Directly connected nodes to the specified user.
2. Indirect Influence(DFS) - The chain of users which are directly or indirectly connected to the specified user.
3. Structural Holes
4. Betweenness Centrality

#Other
Based on the dataset we collected from thementioned code we used a graph tool named GEPHI to visualize our dataset and get the inference.
