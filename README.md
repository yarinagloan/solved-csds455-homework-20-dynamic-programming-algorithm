Download Link: https://assignmentchef.com/product/solved-csds455-homework-20-dynamic-programming-algorithm
<br>
For this assignment, lookup how <em>dynamic programming </em>algorithms work.

Recall the <em>maximum independent set </em>problem: Given a graph <em>G </em>find the largest independent set of vertices of <em>G</em>. An independent set is an induced subgraph that has no edges.

<strong>Problem 1: </strong>Give a dynamic programming algorithm that finds the maximum independent set on a tree <em>T</em>. The algorithm should start at the leaves of the <em>T </em>and work to the root. The algorithm should run in time

O(|<em>T</em>|).

<strong>Problem 2: </strong>Give a dynamic programming algorithm that finds the maximum independent set on a <em>k</em>-tree <em>T<sub>k</sub></em>. The algorithm should start at the “leaves” of <em>T<sub>k </sub></em>(the vertices whose neighborhood is a <em>k</em>-clique) and work to the “root” (a <em>K<sub>k </sub></em>clique that is part of the <em>K<sub>k</sub></em><sub>+1 </sub>clique in the base case in the recursive definition of <em>T<sub>k</sub></em>). The algorithm should run in time O(<em>k</em>|<em>T<sub>k</sub></em>|).

<strong>Problem 3: </strong>Give a dynamic programming algorithm that finds the maximum independent set on a graph <em>G </em>with treewidth <em>k</em>. The algorithm should start at the leaves of the tree and work to the root. The algorithm should run in time O(2<em><sup>k</sup></em>|<em>G</em>|).