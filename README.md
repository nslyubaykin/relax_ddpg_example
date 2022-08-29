# Example DDPG implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_ddpg_example/blob/master/ddpg_tutorial.ipynb) of deep deterministic policy gradient (DDPG) with ReLAx.

DDPG actor was trained on InvertedPendulum-v2 Mujoco Gym environment for 100k env-steps. 

The graph of average return vs environment step is shown below (logs done every 10k steps):

![ddpg_training](https://github.com/nslyubaykin/relax_ddpg_example/blob/master/ddpg_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![ddpg_q_func](https://github.com/nslyubaykin/relax_ddpg_example/blob/master/ddpg_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187177403-f4922a5f-dd06-4ee4-8d49-f20cf18ebb40.mp4
