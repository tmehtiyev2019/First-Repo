Given graph, with 2n vertices and m edges. On every vertex and edge written an integer number. Serik and Zhomart were bored and invented the game on graph. The rules of this game are the following:

Serik starts the game and they alternate turns.
There are exactly n turns for each player.
In every turn Player must choose a non-chosen vertex.
The score of the player is the sum of numbers written in his chosen vertices, plus the sum of numbers written in edge, where both vertices of the edge are chosen by him.
Every player tries to maximize the difference between his and opponent's score.
Of course, Serik and Zhomart are very smart.
Input
The first line contains integers n, m (1 ≤ n, m ≤ 105).

The second line contains integers a1, a2, . . . , a2n (1 ≤ ai ≤ 1000) – numbers on vertices.

Next m lines contain three integer numbers u, v, w (1 ≤ u, v ≤ n, 1 ≤ w ≤ 1000) – vertices u and v are connected, w is number on this edge. Only restriction for graph is: no loop edge.
