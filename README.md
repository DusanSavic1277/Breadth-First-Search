# Breadth first search(BFS) Java implementation

This project demonstrates a simple implementation of the Breadth first search(BFS) algorithm in Java using an adjacency matrix to represent a graph.
The program creates a directed graph, prints its adjacency matrix, and performs a BFS traversal starting from a chosen node.

## Features
- Graph representation using an adjacency matrix
- Custom `Node` and `Graph` classes
- Breadth first search traversal
- Console output showing visited nodes
- Simple and beginner friendly Java code

## What is Breadth first search?
Breadth first search(BFS) is a graph traversal algorithm that explores nodes level by level.  
It uses a queue to keep track of nodes to visit next and ensures that each node is visited only once.

BFS is commonly used for:
- Finding the shortest path in unweighted graphs
- Level order traversal
- Network broadcasting
- Web crawlers

## How it works
1. Nodes are added to the graph.
2. Edges are defined using node indices.
3. The adjacency matrix is printed.
4. BFS starts from the source node (index `0` by default).
5. Each visited node is printed to the console.

## How to run
1. Open the project in any Java IDE(NetBeans, IntelliJ IDEA, Eclipse).
2. Make sure all files are in the same package.

## Technologies used
- Java SE
- Java collections(`ArrayList`, `Queue`, `LinkedList`)
