# Uniform-cost-search-GUI
Romania Map GUI with Uniform Cost Search visualizes how UCS algorithm works 

The aim of the project is to create GUI, where Romania map will be taken as
an input. Apply Uniform cost search algorithm on Romania map and show
the solution in each step. Give a provision to select any source and
destination by the user. On clicking “SUBMIT” button, algorithm execution
will be visualized on the screen. You can use different colors to represent
each step. Final state will be highlighted by red color.

Code Description:

tkinter: Tkinter is used for creating the GUI components.
networkx: Networkx library is used for representing the Romania map as
a graph and for graph traversal operations.

Math: Math library is used for mathematical calculations.
The code can be divided into several parts:

Initialization: The GUI is initialized with the necessary components such
as canvas, buttons, and labels. The Romania map is represented as a
graph, with nodes representing cities and edges representing
connections between cities with corresponding weights (distances).

City Selection: Users can select a source and destination city by clicking
on the respective nodes on the map. Once selected, the source city turns
blue and the destination city turns red.

Uniform Cost Search: Upon clicking the "Submit" button, the Uniform
Cost Search algorithm is applied to find the optimal path between the
selected source and destination cities. The algorithm explores paths
based on their costs and updates the queue accordingly.

Visualization: The search process is visualized step by step on the GUI.
Each step highlights the current city being explored and the path being
traversed. Different colors are used to represent different stages of the
search process.

Final Path Highlighting: Once the optimal path is found, it is highlighted
in red on the map. Additionally, the optimal path and its cost are
displayed as a result.
