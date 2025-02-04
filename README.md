# RL_Luna_Lander
RL agent (DQN)

DQN Agent for Lunar Lander
This project implements the Deep Q-Network (DQN) algorithm using a Replay Buffer and soft target network updates to train an agent in the Lunar Lander environment from the OpenAI Gym library. 
The agent learns to control a lunar module to successfully land on the surface while minimizing fuel consumption and avoiding crashes.

Key Features of the Project:
DQN Algorithm:

Utilizes a neural network to approximate the Q-function.
Incorporates a Replay Buffer to improve training stability.
Implements soft target network updates for smooth parameter adjustments.
Training in the Lunar Lander Environment:

Training is conducted over 1000 episodes.
Employs an adaptive action-selection strategy using the ε-greedy approach.
Results Visualization:

Graph of the average reward per episode.
Graph of the moving average reward over 100 episodes.


This project demonstrates how reinforcement learning techniques like DQN can be applied to complex control tasks in simulated environments.
