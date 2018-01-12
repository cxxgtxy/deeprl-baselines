
# Baselines

My code is based on OpenAI Baselines, which is a set of high-quality implementations of reinforcement learning algorithms.
Our code is aimed to provide more algorithms which is not included by OpenAI baselines, such as C51 and rainbow, as well
 as improvements.
 
These algorithms will make it easier for the research community to replicate, refine, and identify new ideas, and will create good baselines to build research on top of. Our DQN implementation and its variants are roughly on par with the scores in published papers. We expect they will be used as a base around which new ideas can be added, and as a tool for comparing a new approach against existing ones. 

You can install it by typing:

```bash
git https://github.com/cxxgtxy/deeprl-baselines.git
cd deeprl-baselines
pip install -e .
```

- [A2C](baselines/a2c)
- [ACER](baselines/acer)
- [ACKTR](baselines/acktr)
- [DDPG](baselines/ddpg)
- [DQN](baselines/deepq)
- [PPO1](baselines/ppo1) (Multi-CPU using MPI)
- [PPO2](baselines/ppo2) (Optimized for GPU)
- [TRPO](baselines/trpo_mpi)
- [RAINBOW](baselines/rainbow)(DeedMind Rainbow, C51)

