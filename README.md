# Overview
This project provides an interactive visualization of Prim's algorithm for finding Minimum Spanning Trees (MST) in weighted undirected graphs. The visualization helps users understand how the algorithm works step-by-step.

# Features
Interactive graph creation with nodes and weighted edges
Step-by-step visualization of Prim's algorithm
Visual distinction between different edge states:
  MST edges (green)
  Currently considered edges (orange)
  Rejected edges (red)
  Unused edges (gray)
Detailed logging of algorithm steps
Responsive design that works on desktop and mobile devices

# How to Use
1. Setup Graph:
  Enter the number of nodes (2-20)
  Click "Setup Graph"
  Click on the canvas to place nodes
2. Add Edges:
  Click on two nodes to select them (they turn red)
  Enter a weight value
  Click "Add Edge" to connect them
3. Run Algorithm:
  Click "Run Prim's Algorithm" to begin
  Use "Next Step" to progress through the algorith
  Watch the visualization and read the step-by-step log
4. Reset:
  Click "Reset" at any time to start over

# Technical Details
  Built with HTML5 Canvas and vanilla JavaScript
  No external dependencies
  Uses a priority queue (min-heap) implementation for efficient edge selection
  Includes graph connectivity check before running the algorithm

# Live Demo
https://drive.google.com/file/d/1ju4f_phZZ2z70uw_2lbIxyhU6lQAsC8c/view?usp=drive_link

# Screenshots
<img width="946" alt="image" src="https://github.com/user-attachments/assets/ebb8e369-25f4-4c98-aea3-b6c8f52b4f85" />
<img width="940" alt="image" src="https://github.com/user-attachments/assets/175f9a12-e389-4739-877a-e5e8d583bf66" />
<img width="943" alt="image" src="https://github.com/user-attachments/assets/1b7a02e5-a95a-4efd-8ce2-2c9029aa2de5" />
<img width="946" alt="image" src="https://github.com/user-attachments/assets/2b78eecd-b677-4544-a556-c06b9a27bb50" />

# Algorithm Explanation
Prim's algorithm is a greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. This means it finds a subset of the edges that forms a tree that includes every vertex, where the total weight of all the edges in the tree is minimized.

# Complexity
Time Complexity: O(E log V) with priority queue implementation
Space Complexity: O(V + E)
