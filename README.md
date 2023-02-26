# continuous_control
Udacity Deep Reinforcement Learning continuous control project. 
Implemented using the PPO algorithm to control a double jointed arm to reach a target. 

## The environment
The environment is the Unity ML-Agents reacher environment.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

In this project we solved the second version of the environment where each step is a batch of 20 independent agents.

## The solution.
This environment is considered solved if the average score across all agents is above 30 for a 100 consecutive episodes.
