Genetic Algorithm Maze Solver

Overview
This project implements a Genetic Algorithm (GA) to solve a maze optimization problem. It evolves a population of potential solutions to find the shortest path from the start to the goal using selection, crossover, and mutation techniques.

Features
- Maze Representation: The maze is represented as a grid with walls and open paths.
- Genetic Algorithm Implementation: Uses DEAP for evolutionary computation.
- Fitness Evaluation: Solutions are evaluated based on path length and successful goal completion.
- Mutation & Crossover: Random mutations and crossovers enhance genetic diversity.
- Visualization: Matplotlib is used to display the maze and the solution path.

Technologies Used
- Python
- DEAP (Distributed Evolutionary Algorithms in Python)
- NumPy
- Matplotlib

How to Run
1. Clone the repository:
   
   "git clone https://github.com/yourusername/genetic-algo-maze-solver.git"
   
2. Install dependencies:
   
   "pip install matplotlib deap numpy"

3. Run the Jupyter Notebook or execute the script:
   
   "python maze_solver.py"

Results & Insights
- The genetic algorithm evolves solutions to navigate through the maze.
- Mutation and crossover help refine the paths for better solutions.
- Visualization provides insights into how the algorithm explores the search space.
