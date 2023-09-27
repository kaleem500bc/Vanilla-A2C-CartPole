# Reinforcement Learning with Actor-Critic on CartPole

This repository contains an implementation of the Actor-Critic algorithm applied to the CartPole environment using PyTorch. Actor-Critic is a reinforcement learning technique that combines the strengths of both policy-based and value-based methods.

## Overview

- **Actor-Critic**: The code implements the Actor-Critic algorithm, which consists of an actor network (policy) and a critic network (value function). The actor suggests actions, and the critic evaluates those actions.

- **CartPole Environment**: The model is trained and tested on the CartPole-v0 environment from OpenAI Gym. The goal is to balance a pole on a moving cart.

- **Experience Replay**: The code uses experience replay to store and sample past experiences, improving the stability and learning of the agent.

- **TensorBoard Logging**: Training progress, actor loss, and critic loss are logged to TensorBoard for easy monitoring.