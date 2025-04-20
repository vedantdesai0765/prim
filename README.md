# Overview
This project provides an interactive visualization of Prim's algorithm for finding Minimum Spanning Trees (MST) in weighted undirected graphs. The visualization helps users understand how the algorithm works step-by-step.

Features
Interactive graph creation with nodes and weighted edges

Step-by-step visualization of Prim's algorithm

Visual distinction between different edge states:

MST edges (green)

Currently considered edges (orange)

Rejected edges (red)

Unused edges (gray)

Detailed logging of algorithm steps

Responsive design that works on desktop and mobile devices

How to Use
Setup Graph:

Enter the number of nodes (2-20)

Click "Setup Graph"

Click on the canvas to place nodes

Add Edges:

Click on two nodes to select them (they turn red)

Enter a weight value

Click "Add Edge" to connect them

Run Algorithm:

Click "Run Prim's Algorithm" to begin

Use "Next Step" to progress through the algorithm

Watch the visualization and read the step-by-step log

Reset:

Click "Reset" at any time to start over

Technical Details
Built with HTML5 Canvas and vanilla JavaScript

No external dependencies

Uses a priority queue (min-heap) implementation for efficient edge selection

Includes graph connectivity check before running the algorithm
