# GrandSlamWinnersSNA
Grand Slam Finals: Social Network Analysis (1976-2025)
This project applies Graph Theory and Social Network Analysis (SNA) to explore the evolution of men's professional tennis over the last 50 years. The analysis focuses on Grand Slam final matches (Australian Open, Roland Garros, Wimbledon, and US Open) to uncover the underlying structure of the sport.

Project Overview
The goal of this analysis is to identify key tennis eras, generation-defining rivalries, and dominance structures through community detection.

Key Metrics & Algorithms:
Nodes: Tennis players (Grand Slam finalists).

Edges: Connections formed by playing a final against each other.

Weight: The frequency of head-to-head encounters in finals.

Modularity: Used to identify historical epochs and clusters.

Key Insights
Based on the network analysis, the algorithm successfully partitioned tennis history into several distinct clusters:

The "Big Three" Era: A highly dense community consisting of Djokovic, Federer, and Nadal, representing the highest intensity of interactions in tennis history.

Clay Specialists: An interesting grouping of players like Ferrero, Costa, and Kuerten, who dominated Roland Garros in the late 90s but remained relatively isolated from other surface networks.

Classic Eras (70s & 80s): Clearly defined communities centered around the Borg-McEnroe-Connors and Lendl-Becker-Edberg rivalries.

High Modularity: A score of over 0.5 indicates that tennis is not a random sport but a system of strictly defined dynasties and eras of dominance.

Technologies Used:
Python
Pandas (Data manipulation)
NetworkX (Graph construction and metrics)
Matplotlib (Network visualization)
Louvain Method (Community detection)
