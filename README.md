# Minimum Graph Motion Planning

Minimum graph motion planning tackles the problem of finding the path from the start position to the goal position in the smallest number of steps.

We are given a graph, the robot's starting position, the goal position, and a list of obstacles. Both the robot and the obstacles can be moved.

A step consists of moving either the robot or any single obstacle once to a neighboring node.

We tried solving this problem using four algorithms:
1. Brute Force
2. Brute Force with BFS optimizations
3. Variable Neighborhood Search
4. Ant Colony optimization

We also compared the accuracy and the execution time of all of these algorithms.
