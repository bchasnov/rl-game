
### Week 1
- Read OpenAI [spinningup](https://spinningup.openai.com/en/latest/spinningup) introduction to RL @everyone
- Configured cocalc on tortoise to support running x11 desktops and set everyone up on the `2020-rl-game` project @bchasnov
- Created linear quadratic game gym environment with larger state space @zanedma 
- Run spinning up with custom gym environment @singerGUO
- Learn about [pytorch autograd](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html), git, cocalc @JWongDude

### Week 2
- Gradient perturbation controller @zanedma
- Forked competitive policy optimization (copg) repo @JWongDude
- Running experiments in spinning up @singerGUO

### Week 3
- Stackelberg Actor Critic implementation. [Issue](https://github.com/bchasnov/stackgrad/issues/3) @bchasnov
- Wrote tests for LinearQuadraticGame using different hyperparams. Additionally, updated and corrected the     LinearQuadraticGame class. [Issue](https://github.com/bchasnov/stackgrad/issues/1) @zanedma

- Add Cartpole, MountainCar and LunarLander to the Env. Ran Experiments with grids in custom enviroments of cartpole, Plot and viualize the policy 
. [Issue](https://github.com/singerGUO/gym_multiagent_control/issues/1) @singerGUO
- Reviewed Multivariable Calculus, implemented analytical gradient, and learning pytorch. [Issue](https://github.com/bchasnov/stackgrad/issues/2) @JWongDude

### Week 4
- Updated LQ game to fit `gym.Env` specifications to make ready for VPG integration. [Issue](https://github.com/zanedma/reinforcement_lqgame/issues/2). Begin updating (VPG)[https://github.com/bchasnov/spinningup/blob/master/spinup/algos/pytorch/vpg/vpg.py] to work with multiple players and our LQ game. (Issue)[https://github.com/zanedma/reinforcement_lqgame/issues/1]. @zanedma
