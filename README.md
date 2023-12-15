# SARSA Reinforcement Learning Agent

This repository contains a SARSA (State-Action-Reward-State-Action) reinforcement learning agent implemented in Python. The agent is designed to interact with an environment and learn to make optimal decisions through the SARSA algorithm.

## Getting Started

### Prerequisites

Make sure you have the necessary libraries installed. You can install them using:

```bash
pip install numpy matplotlib gym
```

## Usage

1. Import the necessary libraries and the SARSA agent class:
```python
import numpy as np
import matplotlib.pyplot as plt
import gym
from collections import defaultdict
from IPython.display import clear_output
```

2. Create an instance of the SARSA agent:
```python
   sarsa_agent = SarsaAgent(alpha=0.1, epsilon=0.1, discount=0.9, get_legal_actions=get_legal_actions_function)
```

3. Play and train the SARSA agent:

```python
reward = play_and_train(env, sarsa_agent)
```
