# marl_wildfire_control
Multi-Agent Reinforcement Learning for Cooperative Control in Wildfires

Project Details:
  - Created a complex highly stochastic 2D wildfire environment from scratch.
  - Simulated learning of homogenous and heterogenous agents with centralized critic Multi-Agent Deep Deterministic Policy Gradient (MADDPG) Algorithm.
  - Added an attention mechanism to MADDPG to compare between results.
  - Evaluation metrics:
    1. Total number of trees suppressed.
    2. Total number of trees suppressed by both classes of agents in heterogenous scenarios.
    3. Total rewards accumulated.
  - Used Pygame for visualizing the fire spread and agents' actions during the training process.
