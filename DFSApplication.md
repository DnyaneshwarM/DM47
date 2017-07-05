 
Applications – DFS 

1) Finding out if a connected undirected graph is biconnected.A connected undirected graph is biconnected if there are no vertices 
whose removal disconnects the rest of the graph. 
Application in computer networks: ensuring that a network is still connected when a router/link fails. 

2) DFS can be used to solve a maze and can be enhanced to provide road navigation.

3) Solving puzzles with only one solution, such as mazes. (DFS can be adapted to find all solutions to a maze by only including nodes on the current path in the visited set.)

4) Detecting cycle in a graph
A graph has cycle if and only if we see a back edge during DFS. So we can run DFS for the graph and check for back edges. (See this for details)

5)  Searching for solutions in artificial intelligence or web-crawling.

