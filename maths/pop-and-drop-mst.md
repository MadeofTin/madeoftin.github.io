# Pop and Drop
###  Algorithm for finding MSTs [(Minimum Spanning Trees)](https://en.wikipedia.org/wiki/Minimum_spanning_tree)


## Instructions

- Sort Edges by Weight
- For each edge in the graph :
  - Pop the greatest edge from the top.
  - Check if removing that edge broke the graph
    - If it did, drop that edge into your MS
    - If not, Drop it into the trash
