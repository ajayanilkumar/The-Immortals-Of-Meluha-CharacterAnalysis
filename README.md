# The-Immortals-Of-Meluha-CharacterAnalysis

We have used the text version of the novel - The Immortals of Meluha by Amish Tripathi. This is for research/educational purpose only.

### Steps taken in network analysis of the characters in this book:
- Preprocess the text file by removing stop words, chapter title, etc.
- We make a list of characters.
- Extract a social graph of the manually identified characters in the text.
  - Used co-occurrence algorithm.
  - Plotted graph using networkx.
- Calculated the four types of centrality of main protagonists:
  - Degree centrality.
  - Betweenness centrality.
  - Closeness centrality.
  - Pagerank.
- Calculated the global clustering coefficient of the graph and local clustering coefficient of the main protagonist nodes.
- Detected communities using the following methods:
  - K - clique (percolation method).
  - Louvain community detection.
  - Girvann Newman.
- Found the degree distribution, average shortest path, and size of the largest component.
- Created equivalent generative models to compare against the social graph that is extracted: 
  - G(n,p) and G(n,m) generated graph.
  - Preferential attachment.
