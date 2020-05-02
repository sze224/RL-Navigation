# RL-Navigation

Deep Reinforce Learning - Navigation Project Report

Objective 

The Objective of this project is for an agent to navigate in an environment full of bananas. The environment contains blue bananas and yellow bananas, and the agent’s goal is to collect as many yellow bananas as possible while avoiding the blue bananas. Whenever the agent collects a yellow banana, the environment will reward the agent with 1 point and when the agent collects a blue banana, the environment will give the agent a -1 point. This type of objective is perfect for deep reinforcement learning, and in this project the agent will be trained by a Deep Q-Networks and Dueling DQN, where the network will take in the environment state as an input and output the best action for the agent to take. 


Environment and Agent Exploration

In order to fully understand how the agent interacts with the environment, we should first examine the environment state and the available actions that the agent can take. 

In this particular environment, the environment state is a vector with 37 features which represent the agent’s velocity and a ray-based perception of objects around the agent's forward direction. 

As for the agent, there are 4 discrete actions that are available, which are:
0 - move forward
1 - move backward
2 - turn left
3 - turn right

Getting Started

Dependencies
Python 3.6

To run this project, clone the git repo and click run in the juypter notebook
