---
layout: post
title:  "Reinforcement learning for autonomous navigation of UAVs"
date:   2018-03-04
categories: [rl]
description: Experiment with Q-Learning and simple PID control.
tags: reinforcement learning, q-learning, pid, uavs, autonomous navigation
---
## Intro:
<p style="text-align:justify">Autonomous navigation of drones(quadrotors) involve complex level of path planing while adopting classical controls approach. Over the years, machine learning approaches have proven to be a promising alternative to the classical control theory. Reinforcement learning, a sub-domain of machine learning methods, has been extensively explored for path planing and autonomous navigation in structured environments (indoors & outdoors).</p>
<p style="text-align:justify">This post is regarding my experiment with Q-Learning & PID tuning, for autonomous navigation of an ardorne (from start to goal position) in gazebo simulation environment. I have tried to implement the work by Pham, Huy X., et al.<b><a href="https://arxiv.org/abs/1801.05086" class="md-link">Autonomous uav navigation using reinforcement learning.</a></b> arXiv preprint arXiv:1801.05086 (2018).</p>

## Outline:
<p style="text-align:justify">
<li> Implement q-learning based RL algorithm for autonomous navigation of ArDrone in a discrete indoor space.</li>
<li> PID control is also coupled with the RL approach.</li>
</p>

## What's Q-Learning
<p style="text-align:justify">In a RL setting, the agent regularly updates its knowledge of the environment through constant interactions and feedbacks. Hence we assume the environment to be a Markovian tuple [S, A, T, R] where the next state (S<sub>t+1</sub>) and reward (R<sub>t+1</sub>) of the agent depends on the current state (S<sub>t</sub>). (to be continued)</p>

## Prerequisites/Requirements:
<p style="text-align:justify">These include the system requirements and packages used for the simulation setup.</p>
<p style="text-align:justify">
<li> Ubuntu 16.04</li>
<li> ROS Kinetic</li>
<li> Gazebo 7</li>
<li> ArDrone Autonomy ROS Package</li>
<li> gym: 0.9.3</li>
<li> TensorFLow 1.1.0 (preferrable with GPU support)</li>
<li> Python 2.7</li>

## Project Video

<iframe width="560" height="315" align="center" src="https://www.youtube.com/embed/SDqPfhUeoCo" frameborder="1" allow="accelerometer; autoplay; encrypted-media" allowfullscreen></iframe>

## References:
<p style="text-align:justify">

<li> Pham, Huy X., et al. <b><a href="https://arxiv.org/abs/1801.05086">Autonomous uav navigation using reinforcement learning.</a></b> arXiv preprint arXiv:1801.05086 (2018).</li>
<li> Mnih, Volodymyr, et al. <a href="https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf"><b>Human-level control through deep reinforcement learning.</b></a> Nature 518.7540 (2015)</li>

</p>
