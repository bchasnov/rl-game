# Stackelberg RL (Summer 2020)

**Goal:** to use Stackelberg implicit learning dynamics for reinforcement learning.

Possible algorithms:
1. Single player environment. Treat the actor (or critic) as a leader in actor-critic algorithms.
2. Two-players environment, a leader and a follower.
3. $n$-players environment, a leader and multiple followers.

Possible two-player environments
1. Linear quadratic games
2. bimatrix games
3. gridworld games (e.g. Markov soccer)
4. bubbleworld games (e.g. particle collision avoidance)
5. multi-player modified gym environments (e.g. two lunar landers or two cartpoles)
6. new environment design with 'game theoretic' aspects


To systematically run and record experiments, we will use [ExperimentGrid](https://github.com/openai/spinningup/blob/master/spinup/utils/run_utils.py#L240) to do grid searches with the following inputs and outputs.

Experiment bench input:
1. Type of algorithm (simgrad, stackgrad)
2. Hyperparameters (learning rates, regularization, initialization, network architecture)

Experiment bench output:
1. Convergence plots of costs and first-order derivatives
2. Eigenvalues of second order derivatives
3. Checkpoints


**Github Repositories:**

- [`bchasnov/stackgrad`](https://github.com/bchasnov/stackgrad): implements the Stackelberg update 
- [`zanedma/reinforcement_lqgame`](https://github.com/zanedma/reinforcement_lqgame): linear quadratic game environment
- [`JWongDude/FruitLoops`](https://github.com/JWongDude/FruitLoops): forked from `manish-pra/copg`, compares stackgrad with competitive gradient descent in RL environments.
- [`singerGUO/gym_multiagent_control`](https://github.com/singerGUO/gym_multiagent_control): gym environments for games
- [`ratlifflj/2020sumuwreadgrp`](https://github.com/ratlifflj/2020sumuwreadgrp): summer reading group codebase
- [`fiezt/ICML-2020-Implicit-Stackelberg-Learning`](https://github.com/fiezt/ICML-2020-Implicit-Stackelberg-Learning): reference code for Stackelberg learning update

