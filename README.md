# Shortest Path Game

This project is a Python implementation of a game that challenges the player to find the shortest path from the upper-left corner to the lower-right corner of a rectangular grid. The grid consists of cells with random values ranging from 0 to 9. The number on each cell represents the amount of time steps the player spends on that cell when moving through it. The objective is to optimize the path to reach the destination as quickly as possible.

## Game Implementation

The game is structured and flexible, allowing for the selection of different game modes and parameters. The implementation should be designed in a modular and organized manner to enhance reusability and code readability. Here are the key components and features to consider when implementing the game:

- **Grid**: Create a rectangular grid of size `height x width` with randomly generated values between 0 and 9 for each cell.
- **Agent**: Represent the player's agent that moves through the grid. Start the agent at the upper-left corner and aim to reach the lower-right corner.
- **Movement**: Enable the agent to move to adjacent cells in the grid, spending as many time steps as the value on that cell.
- **Game Modes**: Implement different game modes or difficulty levels, such as a timed mode or a mode with obstacles, to provide variety and challenge to the player.
- **Input Handling**: Allow the user to input their desired game parameters, such as grid size and game mode, to provide customization options.

## Heuristic Algorithm

Develop your own heuristic algorithm to find short paths in the grid. This algorithm should be a baseline and not necessarily optimized for speed or efficiency, but it should outperform random movements. Consider the following points when implementing the heuristic algorithm:

- **Simple Criteria**: Identify simple criteria and strategies to determine the next cell the agent should move to based on the current position.
- **Path Evaluation**: Evaluate the potential paths based on the heuristic criteria and select the most promising one for the agent to follow.
- **Performance**: Although optimization is not the primary goal, ensure that the algorithm performs reasonably well compared to random movements.

## Dijkstra's Algorithm Implementation

Implement Dijkstra's algorithm to find the shortest path between the starting point (upper-left corner) and the destination (lower-right corner) in the grid. Use a simple priority queue-based approach similar to the original algorithm. The following guidelines will assist you in implementing this part effectively:

- **Code Customization**: Write your own code for Dijkstra's algorithm instead of relying on pre-existing sophisticated implementations available online. The objective is to demonstrate your ability to implement the algorithm.
- **Priority Queue**: Utilize a priority queue to store and process the cells, prioritizing the ones with the shortest accumulated path lengths.
- **Detailed Comments**: Provide detailed comments explaining each step of your implementation to enhance readability and understanding.

## Statistical Analysis

Plan and implement a statistical analysis to characterize the length of the shortest path based on various parameters of the grid. Consider the following aspects when conducting the analysis:

- **Grid Parameters**: Investigate the impact of different grid sizes on the length of the shortest path. Vary the height and width of the grid and record the corresponding path lengths.
- **Cell Number Distribution**: Explore the influence of different distributions from which the cell numbers are generated. Consider different probability distributions and generate random cell numbers based on those distributions.
- **Measurement and Evaluation**: Determine suitable metrics to measure and evaluate the length of the shortest path. Consider average path length, standard deviation, and other relevant statistical measures.

Ensure that you document your statistical analysis process, including the chosen parameters, distributions, measurement techniques, and results. Providing clear and concise explanations will help others understand your methodology and findings.

## Conclusion

This project assesses your Python skills, including your ability to plan
