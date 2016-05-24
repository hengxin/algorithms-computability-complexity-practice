# Algorithm Analysis

## Manipulation of Asymptotic Notations

- [Why are Complexity Notations Called Asymptotic? (from cs.se)](http://cs.stackexchange.com/q/53931/4911)

- [Using the Master theorem on a recurrence with non-constant `a` (from cs.se)](http://cs.stackexchange.com/q/52229/4911)

  `To solve $T(n)  = 3^n T(\frac{n} 3) + O(1)$; try $\log T(n)$`

- [Can I simplify the recurrence $T(n)=2T((n+1)/2)+c$ by ignoring the "$+1$" part?](http://cs.stackexchange.com/q/52298/4911)
 
  `Try and Prove.`

- [Solving a recurrence relation with $\sqrt{n}$ as parameter](http://cs.stackexchange.com/q/6410/4911)

  `By unfolding OR By substitution.`

## Amortized Analysis

- [Potential method for dynamic binary search (from cs.se)](http://cs.stackexchange.com/q/37822/4911)

## Adversary Argument

- [Why does merging two sorted arrays take 2N - 1 comparisons?](http://cs.stackexchange.com/q/57726/4911)

# Algorithm Design

## Search and Selection

- [How to find the kth smallest element in the union of two sorted arrays? (from stackoverflow)](http://stackoverflow.com/q/4607945/1833118)

- [Selection problem on the union of two ordered dictionaries (from cs.se)](http://cs.stackexchange.com/q/33106/4911)

- [Finding kth smallest number from n sorted arrays (from stackoverflow)](http://stackoverflow.com/q/8753345/1833118)

  `A generalization to multiple sorted arrays`

- [Find local minimum in `$n \times n$` matrix in `$O(n)$` time](http://stackoverflow.com/q/18525179/1833118) 

  `This is a good example to demonstrate the design of divide and conqure algorithm.`

## Graph Algorithms

### Trees

- [Determining if an undirected connected graph is minimally connected (from cs.se)](http://cs.stackexchange.com/q/52157/4911)

  `Def: Minimally Connected: it is connected and there is no edge that can be removed while still leaving the graph connected. Actually it is a tree (defined by any two of "connected, n-1 edges, no cycle")`

### DFS and BFS

- [Algorithm to find shortest lightest path in a graph from source](http://cs.stackexchange.com/q/51721/4911)

  `This problem can be solved by both BFS and Dijkstra's SSSP algorithm.`
- [Lowest common ancestor](https://en.wikipedia.org/wiki/Lowest_common_ancestor)
- [Algorithm to find diameter of a tree using BFS/DFS. Why does it work?](http://cs.stackexchange.com/q/22855/4911)
  
  `Run BFS on any node s in the graph, remembering the node u discovered last. Run BFS from u remembering the node v discovered last. d(u,v) is the diameter of the tree.`

### Cycles
- [Check existence of odd-length directed cycle](http://algs4.cs.princeton.edu/42digraph/); see also [@cs-stackexchange](http://cs.stackexchange.com/q/3517/4911)

  `Solution. We claim that a digraph G has an odd-length directed cycle if and only if one (or more) of its strong components is nonbipartite (when treated as an undirected graph).`
- [Find odd-length directed cycle](http://cs.stackexchange.com/q/57565/4911)

  `Using BFS.`
- [Shortest directed cycle](http://algs4.cs.princeton.edu/42digraph/)
  - Using Floyd-Warshall algorithm $O(n^3)$
  - Solution (O(nm)): run BFS from each vertex s. The shortest cycle through s is an edge v->s, plus a shortest path from s to v.

- [Finding length of shortest cycle in undirected graph](http://stackoverflow.com/q/20847463/1833118)

  `It explains why some BFS/DFS fail`.
- [An efficient algorithm to find a shortest cycle including a specific vertex $v$ in undirected graph](http://cs.stackexchange.com/a/57688/4911)

  `BFS on this undirected graph from $v$; terminates when reaching $v$ again (BFS should be slightly modified)`

### Path problems

- [Dijkstra's algorithm with different color nodes](http://cs.stackexchange.com/q/33056/4911)

  `The task is to determine if a colorful path exists, and if so, find one that contains a minimum number of white nodes.`

- [Minimax path problem](http://cstheory.stackexchange.com/questions/5195/reference-for-fast-algorithm-for-bottleneck-shortest-paths) 

> Specifically, given vertices `$s$` and `$t$` in an undirected graph with edge weights, you want the shortest path from `$s$` to `$t$`, where the length of a path is the maximum edge on that path. This can be solved in `$O(n+m)$` time by finding the median edge weight and (carefully) recursively deleting half the edges.

- [How does following algorithm for finding longest path in tree work?](http://www.quora.com/How-does-following-algorithm-for-finding-longest-path-in-tree-work)

- [Longest path in an undirected tree with only one traversal](http://cs.stackexchange.com/q/11263/4911)

  `We perform a depth-first search in post order and aggregate results on the way, that is we solve the problem recursively.`

- [Sketch of Eulerian Circuit Algorithm](http://www.ms.uky.edu/~lee/ma515fa10/euler.pdf)

- [Hierholzer's algorithm for finding Eulerian Circuit (wiki)](https://en.wikipedia.org/wiki/Eulerian_path#Hierholzer.27s_algorithm)

### Minimum spanning tree

- [Do the minimum spanning trees of a weighted graph have the same number of edges with a given weight?](http://cs.stackexchange.com/questions/2204/do-the-minimum-spanning-trees-of-a-weighted-graph-have-the-same-number-of-edges)

  `The answer is Yes.`
- [The MST property](http://cs.stackexchange.com/q/57477/4911)

  `A spanning tree T is an MST iff T has the MST property.`
  
- [Finding minimum spanning tree with O(|V|)](http://cs.stackexchange.com/q/19221/4911)
  
  `The extra constraint is $|E| = |V| + 10$`

## Greedy Algorithms

- [Greedy strategy for computing the minimum number of rays that hit all balloons (from cs.se&&Jeff)](http://cs.stackexchange.com/q/52291/4911)

  `find an $O(n \log n)$ algorithm`

## Dynamic Programming

- [Algorithm to find the shortest walk with k leaf nodes on a tree](http://cs.stackexchange.com/q/51738/4911)

  `Dynamic programming on a tree structure.`

- [Find a maximum sum in matrix, subject to special constraint (from cs.se)](http://cs.stackexchange.com/q/51995/4911)

## More Mathematical than Algorithmic

- [Shortest path in divisors graph](http://cs.stackexchange.com/q/52108/4911)

  `Relationship with gcd or lcm`

## Recreational

- [Efficient algorithm for 'unsumming' a set of sums (from cs.se)](http://cs.stackexchange.com/q/45525/4911)

## Miscellaneous
