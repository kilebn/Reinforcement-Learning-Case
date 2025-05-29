Reinforcement Learning Demo: CartPole with Stable-Baselines3
This group project demonstrates fundamental reinforcement learning concepts using the CartPole-v1 environment. We use the Advantage Actor-Critic (A2C) algorithm from the stable-baselines3 library to train an agent to balance a pole on a moving cart.

The project consists of three main parts:

Environment Setup and Baseline Behavior
We configure the CartPole environment and record the behavior of an untrained agent. This serves as a reference for the model's learning progress.
Agent Training and Evaluation
The agent is trained using the A2C algorithm with appropriate callbacks for evaluation and checkpointing. Performance metrics such as reward progression are visualized and compared against baseline performance.
Policy Visualization and Interpretation
The trained agent is evaluated visually via rendered videos to showcase its learning outcomes. We compare intermediate and final policies and discuss reward optimization and stability.
Limitations: The model is trained on a simplified environment and does not generalize beyond the CartPole task. The goal is didactic—providing an intuitive introduction to policy-based RL methods
