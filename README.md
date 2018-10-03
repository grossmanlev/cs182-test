
# CS 182: Artificial Intelligence
# P3: Markov Decision Processes and Reinforcement Learning

* Fall 2018
* Due: 11:59PM, Wednesday, October 24, 2018

## Simulated Annealing (4 points)

We will be solving the classic knapsack problem using Simulated Annealing (SA). Given some items, each item consisting of a weight and value, we want to select the items so as to maximize the total value while staying under some weight limit. Inside simulated_annealing.py is the starter code comparing a greedy solution to your SA solution. The function simulated_annealing should return a list of values your algorithm has accepted (value meaning the total value of your chosen items). Running the file will generate a plot comparing your SA values to the greedy solution. Submit your code on Gradescope.

Hint: You should beat the greedy solution.
Notes: The python file requires that you have numpy and matplotlib installed.