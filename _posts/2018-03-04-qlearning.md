---
layout: post
title:  "Reinforcement learning for autonomous navigation of UAVs"
date:   2018-03-04
categories: [rl]
description: Experiment with Q-Learning and simple PID control.
tags: reinforcement learning, q-learning, pid, uavs, autonomous navigation
---
## Intro:
- Autonomous navigation of drones(quadrotors) involve complex level of path planing while adopting classical controls approach.
- Over the years, machine learning approaches have proven to be a promising alternative to the classical control theory. Reinforcement learning, a sub-domain of machine learning methods, has been extensively explored for path planing and autonomous navigation in structured environments (indoors & outdoors).
- This post is regarding my experiment with Q-Learning & PID tuning, for autonomous navigation of an ardorne (from start to goal position) in gazebo simulation environment.
- I have tried to implement the work by Pham, Huy X., et al.<b><a href="https://arxiv.org/abs/1801.05086" class="md-link">Autonomous uav navigation using reinforcement learning.</a></b> arXiv preprint arXiv:1801.05086 (2018).

## Outline:
- Implement q-learning based RL algorithm for autonomous navigation of ArDrone in a discrete indoor environment.
- Also PID control is also coupled with the RL approach.

## What's Q-Learning
- In a RL setting, the agent regularly updates its knowledge of the environment through constant interactions and feedbacks. Hence we assume the environment to be a Markovian tuple [S, A, T, R] where the next state (S<sub>t+1</sub>) and reward (R<sub>t+1</sub>) of the agent depends on the current state (S<sub>t</sub>). (to be continued)

## Project Video

<iframe width="560" height="315" align="center" src="https://www.youtube.com/embed/SDqPfhUeoCo" frameborder="1" allow="accelerometer; autoplay; encrypted-media" allowfullscreen></iframe>

## References:
- Pham, Huy X., et al. <b><a href="https://arxiv.org/abs/1801.05086">Autonomous uav navigation using reinforcement learning.</a></b> arXiv preprint arXiv:1801.05086 (2018).
- Mnih, Volodymyr, et al. <a href="https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf"><b>Human-level control through deep reinforcement learning.</b></a> Nature 518.7540 (2015)
