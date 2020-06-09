_______________________________________________________________________________________________________________________________________
-We will perform a network analysis on a famous social network: Facebook.
-The aim of this project is to implement friend recommendation system, community detection and finding influencers on a Facebook data-set.
-Data set: http://networkrepository.com/socfb-Carnegie49.php  (Contains 6.6k nodes, 250k edges)

-------------------------Friend Recommendation System---------------------------------
Flow
Initial analysis->Generate required features->Run classification model to predict friends

Features generated:
1)Jaccard similarity
2)Shortest path
3)Adar index
4)Harmonic centrality
5)Common neighbours
6) Betweenness centrality
7)Eigenvector centrality

Different classification models and accuracies:

Classifier Accuracy (%)
Random Forest Classifier= 96.449
XGBoost Classifier= 97.445
SVM = 97.957
Passive Aggressive Classifier =94.812

--------------------------Community Detection Algorithms------------------------
1)Girvan Newman Algorithm
2)Louvain Algorithm


