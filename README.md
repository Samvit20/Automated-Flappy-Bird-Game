# AI-Flappy-Bird
Flappy Bird Automation using NEAT Algorithm

# Abstract

A large number of algorithms to generate behaviors of game agents have been developed in recent years. Most of them are based on artificial intelligence techniques that need a training stage. In this context, this paper proposes a minimal training strategy to develop autonomous virtual players using the NEAT neuroevolutionary algorithm to evolve an agent capable of playing the Flappy Bird game. NEAT was used to find the simplest neural network architecture that can perfectly play the game. The modeling of the scenarios and the fitness function were set to ensure adequate representation of the problem compared to the real game. The fitness function is a weighted average based on multiple scenarios and scenario-specific components. Coupling the minimal training strategy, a representative fitness and NEAT, the algorithm had a short convergence time (around 20 generations), with a low complexity network and achieved the perfect behavior in the game.

This project proposes a minimal training strategy to develop autonomous virtual players using the NEAT (neuroevolutionary algorithm) to evolve an agent capable of playing the Flappy Bird game.

NEAT was used to find the simplest neural network architecture that can perfectly play the game.

# Used Packages:

● Pygame

● Neat-python

● Time

● OS

● Random



# How to run

1) Clone the repository.
2) Run FPB.py in a python IDE.

# Conclusion

In this project we propose a minimal training strategy to generate agents capable of achieving optimal scores in the game Flappy Bird. By using scenarios with only three different types of obstacles to train the agents, they evolved a neural network to stay alive indefinitely in an environment with endless pairs of pipes with random heights.

The fitness calculation used ensured that the objective of an agent in a reduced environment represented its goal in a real run of the game. Because the obstacles used have gaps near the environment borders and an intermediate one, when the agent manages to maximize its result in these three cases it then masters all possible variations within these limits. 

Considering that NEAT always searches for the simplest solution to a problem and that the fitness presented together with the division into three scenarios help the NEAT find a perceptron network architecture using a single species, this solution is the simplest. The techniques discussed in this work helped the algorithm to find this solution in a short time, thus proving its effectiveness.


# Output

![project2](https://user-images.githubusercontent.com/66082800/153639765-f5252b48-e782-452a-aa16-f377fbc4827c.jpg)
