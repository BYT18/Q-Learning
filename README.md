# Trolley Cart Problem Solver using Q-Learning with Neural Networks

## Overview

This high school project implements a solution to the trolley cart problem using Q-learning with neural networks. The trolley cart problem is a classic reinforcement learning problem where a cart must navigate to a goal while avoiding obstacles. The implementation uses a neural network to approximate the Q-values for state-action pairs, allowing the agent to learn a policy for optimal action selection.



https://github.com/BYT18/Q-Learning/assets/68192622/2d5b0542-fb92-48dd-ae5e-373c8d1eb5b2



## Dependencies

- Python 3.x
- PyTorch
- OpenAI Gym

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/trolley-cart-q-learning.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the main script to start training the agent:

```bash
python train.py
```

2. Monitor training progress and results through console output and visualization tools provided.

## Project Structure

- `train.py`: Main script for training the agent.
- `policy.py`: Contains the neural network model for approximating Q-values.
- `utils.py`: Utility functions for environment setup, training, and visualization.
- `README.md`: Project documentation.

## Hyperparameters

- `steps`: Number of moves made before an episode ends or a goal is reached.
- `epsilon`: Probability of taking a random action instead of choosing the action with the highest Q-value.
- `gamma`: Discount factor for future rewards.
- `episodes`: Number of iterations to train the agent.
- `learning_rate`: Learning rate for the neural network optimizer.
- `tau`: Number of episodes until the target network is updated.

## Results

The project achieves successful navigation of the trolley cart to the goal while avoiding obstacles. Success rates, training loss, and other performance metrics are logged during training for analysis.
