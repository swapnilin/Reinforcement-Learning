# Q-Learning on Frozen Lake

This project demonstrates the implementation of the Q-learning algorithm on the classic Frozen Lake environment provided by OpenAI Gym. The notebook explores how an agent learns to navigate the frozen lake to reach the goal while avoiding holes.

## Features

- Implementation of the Q-learning algorithm.
- Hyperparameter tuning for effective learning.
- Visualization of the learning process through reward plots.
- Optimal Q-table computation.

## Environment Details

- **Environment**: FrozenLake-v1 (4x4 grid, slippery surface).
- **Goal**: Navigate the agent from the start position to the goal while avoiding holes.

## Q-Learning Overview

Q-learning is a model-free reinforcement learning algorithm. The agent learns an optimal policy by iteratively updating a Q-table, which maps states and actions to expected future rewards.

### Key Components:

- **Learning Rate (alpha)**: Determines how much new information overrides old information.
- **Discount Factor (gamma)**: Weighs the importance of future rewards.
- **Epsilon-Greedy Strategy**: Balances exploration and exploitation.

## Installation

Ensure you have the following dependencies installed:

- Python 3.7+
- OpenAI Gym
- NumPy
- Matplotlib

Install the required packages using pip:

```bash
pip install gym numpy matplotlib
```

## Customization

Feel free to adjust the hyperparameters in the notebook to experiment with the agent's performance:

* Number of episodes
* Learning rate (alpha)
* Discount factor (gamma)
* Exploration-exploitation tradeoff (epsilon)

