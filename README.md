# A*-Visualizer-
<img width="802" alt="Screenshot 2023-07-15 at 6 13 07 PM" src="https://github.com/MitSheth7/A-Visualizer-/assets/88057396/bd385a80-32da-4fea-af35-f06a64eb584c">

In this project, I have implemented the A* Pathfinding Algorithm using Python and created a visual representation of the algorithm's operation using the Pygame library.

Purpose
The main purpose of the A* Pathfinding Algorithm is to find the shortest path between two points on a grid while avoiding obstacles or barriers in the most efficient manner. It's a widely used algorithm in pathfinding and robotics to plan routes for agents from a starting position to a goal location.

How it Works
The A* Algorithm combines elements of Dijkstra's algorithm (to find the shortest path) with a heuristic function to guide the search and prioritize exploring the most promising paths first. The heuristic function estimates the distance from a given spot to the destination point, which helps in making better decisions during the search process.

Visualization
To make the A* Algorithm easy to understand, we have visualized its operation using the Pygame library. The GUI displays a grid where each cell represents a spot, and it allows you to set the start and end points by left-clicking on the grid. You can also add barriers (obstacles) to the grid by left-clicking and dragging the mouse. Right-clicking on a spot removes barriers or resets the start and end points.

Finding the Path
Once the start and end points are set, you can trigger the algorithm by pressing the spacebar. The algorithm will then begin exploring the grid to find the shortest path between the start and end points, avoiding the barriers if necessary.

nstructions
Here are the instructions to use the application:

Clone the repository using the provided link.
Navigate to the project directory in your terminal.
Run the script by executing python Visualizer.py.
Left-click on the grid to set the start and end points.
Left-click and drag the mouse to create barriers on the grid.
Right-click on a spot to remove barriers or reset the start/end points.
Press the spacebar to start the A* algorithm and find the shortest path.


