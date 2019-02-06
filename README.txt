Name: Ayush Patel
StudentId -  801022369
 
Program Description: 
This project has program implementing Dijkstra's Algorithm for Open Shortest Path using min-heap for obtaining the maximum possible efficiency. 
Programming Language : JAVA
Compiler Version: JDK 1.8.0_161

Compile the program:

Before building the java class file make sure java(i.e jdk1.8) is installed in the system.

Command to build java class files: javac filename.java

Run the Program: Command to run java program: java ClassName InputfileName < QueryfileName > OutputfileName

Data Structures used - 
1. LinkedList data structure is used to represent the edges of the Graph.
2. TreeSet data structure is used to store the visited nodes. 
3. Heap data structure is used to implement the Dijkstra's algorithm and is used to create min binary heap
4. HashMap data structure is used to store information about the vertex. 

Implementation:

Implementation code is in single file Graph.java which has complete 5 tasks required for the project. The algorithm implemented is an algorithm used to find the shortest path between nodes in graph called as Dijkstra's Algorithm. 

Task:
1. Building the Graph: Using network input file we will build our graph. For each input link, two directed edges are added one in each direction.
2. Changes to the Graph: The Graph class implements all the operations to be exceuted while making changes in the class.
3. Finding the Shortest Path: Using Dijkstra's algorithm we will compute the shortest path distance, and we have implemented using Heap Data structure (Min priority queue).
4. Print Graph: Graph is printed using Treeset data structure such that it sorts the graph in alphabetical order.
5. Reachable Vertices: For every vertex, we have find the reachable vertices in alphabetical order from every other vertex. 

Classes used to achieve the implementation are:
1. Binaryminheap: This class is used to efficiently design Dijkstra's Algorithm using concept of minimum priority queue.
2. Graph: Build the Network Graph using input file and perform operations based on query file on the network. This is the main class. 
3. Exception_for_Graph: Used to signal violations of preconditions for shortest path algorithms.
4. Vertex: Vertex class is used to represent vertex of the graph.
5. Edge: Edge class is used to represent edges of the graph.
6. Path: Path class stores name and distance of path.
7. Pair: Pair class represents the String pairs.
     
Prerequisite Conditions -
1. The txt file containing queries should have "quit" query written at last so that the program terminates execution after reading the "quit" query.
2. The graph file should be in the correct format as specified otherwise it will throw an exception saying "ill-formatted file"

What works and fails?
All the desired functionalities or tasks works well when the prerequisite conditions are met. 
