# PythonViso
## Jan 28th Updates: ##
#### - Color-coding of Nodes Rules:
 1. Colors are based on the relationships in the sub-graph (sub-edges), not the entire graph
 2. If one node is a suspect in one relationship in the sub-edges, it will be considered suspect;
 3. If one node has never been a suspect and is a victim in one of relationship in the sub-edges, it will be considered victim
##
#### - Color-coding of Edges Rules:
 1. Colors are based on the node colors that are already set, not based on the particular case
 2. "Black" shows that individuals in question are both criminals and know each other because they are involved in the same case
 3. "Grey" shows the victim-suspect relationship
 4. Insiginificant relationships such as "victim-victim" are omitted in the graph (set to be white)
##
#### - Centrality Measure and size of the nodes:
 1. Centrality options are three: betweenness, closeness and degree
 2. The size of the nodes are based on the centrality measurement of the nodes, the more significant the individual is, the bigger size the node has
##
#### - 3d graph and toggling implemented
