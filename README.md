# Download Instructions
To download the repository open a shell and type:
git clone https://github.com/livecat-ai/continuous_control.git

# continuous_control
Udacity Deep Reinforcement Learning continuous control project. 
Implemented using the PPO algorithm to control a double jointed arm to reach a target. 

## The environment
The environment is the Unity ML-Agents reacher environment.

[Environment example](https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif)

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

In this project we solved the second version of the environment where each step is a batch of 20 independent agents.

### The solution.
This environment is considered solved if the average score across all agents is above 30 for a 100 consecutive episodes.

## Getting started
The reacher environment is only supported in an older version of ML-Agents. This makes it impractical to install on your local machine.
Hence the only way to run the notebook is on the Udacity platform.

Most of the code is included within the PPO.ipynb notebook and should run without any user setup. The only except being workspace_utils.py which needs to be in the same directory as PPO.ipynd.

## Insturctions
To run the code, upload the contents of this git repository to an appropriate workspace on the Udacity Deep Reinforcement Learning platform.
* Once the Udacity workspace is up and running, click the Jupyter icon at the top of the page.
* This will take you to a list of files.
* Double click on PPO.ipynb
* Step through the code cell by cell. Or select run all from the "cell" menu at the top of the workbook.


