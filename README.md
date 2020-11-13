# TenFor
This tool is based on the paper "TenFor: A Tensor-Based Tool to Extract Interesting Events from Security Forums" published in ASONAM 2020. TenFor groups the similar thinking users from the security forums using tensor decompsition and then extracts impportant events from each groups. Also provides nice visualization to showcase the output of different analysis performed.

Features:
1. Uses Tensor Decomposition to cluster similar kind of threads, users working in similar time frame.
2. Tag each cluster using user-defined labels.
3. Reports scree-plots and basic statistics of the clusters
4. Provides a behavioral profiling of the clusters.
5. Present top k user, thread and time from each cluster.
6. Provies a nice StoryLine  view of the important events per cluster.


Disclaimer: 
This code may not match with the paper. We are providing just a backbone of the code here. We will keep updating this code continuously. If you need more information, please contact me directly at risla002@ucr.edu


To Run the code:

Prerequisite Packages from python v 3.6:
pandas, numpy, matplotlib, tensorly, random, datetime, unidecode, pickle, gensim.

Prerequisite work:
Create two folders: "figures" and "figuresAnomalous" in the current directory where this code will be stored. these folders will contain the graphs drawn for analysis and visualization purpose.

