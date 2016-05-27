# Challenging Algorithm Problem Set

This document collects challenging algorithm problems (mostly along with solutions).

## Sorting

- [Recover sequence from randomly ordered consecutive pairs (from cs.se)](http://cs.stackexchange.com/q/52428/4911)

  This is an interesting problem given as an exercise [Ex 24; Chapter 5: Sorting] in TAOCP, Vol3, 2nd Edition. 
  Knuth gives a solution attributed to Norman Hardy, 1967. 
  - [ ] Blog article?
  
## Minimum Spanning Tree
- [Minimum bottleneck spanning tree@wiki](https://en.wikipedia.org/wiki/Minimum_bottleneck_spanning_tree)

  The wiki article includes algorithms for both undirected graphs and digraphs.
  - [ ] Blog article?
  
## Paths in Graphs

- [Bottleneck shortest path@mathoverflow](http://cstheory.stackexchange.com/q/5195/12739)
  
  This can be solved by modifying Dijkstra's algorithm for SSSP.

  This can be solved in $O(n+m)$ time by finding the median edge weight and (carefully) recursively deleting half the edges.
  
  It is also called the [Widest path problem@wiki](https://en.wikipedia.org/wiki/Widest_path_problem) or the max-min path problem.
