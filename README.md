# Reinforcement Learning - Sapienza 2020

The project consists in testing the algorithm on an environment that is assigned to us and analyze the data that it is
working in that environment. In this project, we use **Reinforcement Learning**, which is a technique that allows the agent to learn a certain behavior
depending on the environment submit to it with methods based on the concept of reward.


In my case, I was given the **DQN** algorithm to test on *Assault* environment of **OpenAi Gym**. The algorithm was provided to us using the ”stable baselines” library.

## Environment

In the environment ”Assault-v0” the observation consists in the image, the k frames received or it can be the ram;
instead in ”Assault-ram-v0” is executed the observation is the ram.
The agent acts following the commands of ATARI 2600: NOOP, FIRE, RIGHT, LEFT, RIGHTFIRE, LEFTFIRE,
UPFIRE.

The reward starts from zero with each episode of the game and increases every time a spacecraft is hit, so the reward
depends on the action done by the agent. When the agent dies, it returns to the initial state in which the reward is
set to zero.

Our *aim* is to **train the game** using DQN algorithm, in particular, to modify *hyperparameter* in order to obtain quite
significant results.

## Requirements

Use google colab to run the code, using the GPU.
[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
