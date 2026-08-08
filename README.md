# 🐦 Flappy Bird RL

A Reinforcement Learning project where an AI agent learns to play Flappy Bird using the Gym Flappy Bird environment.

The project explores how an autonomous agent can learn an optimal policy through trial and error by interacting with the environment and maximizing cumulative rewards.

---

## Features

- OpenAI Gym / Gymnasium compatible Flappy Bird environment
- Reinforcement Learning-based agent training
- Episode-wise reward tracking
- Model evaluation after training
- Visualization of the trained agent's gameplay

---

## Reinforcement Learning Pipeline

1. Initialize the Flappy Bird environment
2. Observe the current game state
3. Select an action using the learning policy
4. Execute the action and receive a reward
5. Update the agent based on the observed transition
6. Repeat until convergence

---

## Environment

The project uses the **Gym Flappy Bird** environment, allowing the agent to learn directly from interactions with the game.

State information typically includes the bird's position, velocity, and relative positions of the upcoming pipes.

Available actions:

- Do Nothing
- Flap

---

## Tech Stack

### Reinforcement Learning

- Python
- Gym / Gymnasium
- NumPy

### Visualization

- Matplotlib

### Notebook

- Jupyter Notebook

---

## Future Improvements

- Deep Q-Network (DQN) implementation
- Double DQN
- Prioritized Experience Replay
- Hyperparameter tuning
- Reward shaping
- Training performance visualization
- Comparison between different RL algorithms

---

## Author

Vansh

Built as a personal reinforcement learning project while exploring how agents learn through interaction with an environment.