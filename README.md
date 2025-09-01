# CUB Reinforcement Learning, Fall 2025

Unlike classical machine learning, in reinforcement learning, the algorithm does not receive a training dataset as input. Instead, learning occurs through the "trial and error" method: the agent must gather data independently through interaction with the environment and, based on the collected experience, learn to maximize the received feedback—reinforcement or reward. The course is aimed at studying recent algorithms that demonstrate state-of-the-art results in many discrete and continuous control tasks by combining classical theory with the deep learning paradigm.

**Instructor**: Dmitry Kropotov

**Timetable**: the classes are scheduled on Fridays in the classroom EH-8 at the time slot 10:30 - 13:15.

**Telegram chat for questions and discussion**: [link](https://t.me/+d2i1n4ag8oE2N2Vi)

**Assignments**: All assignments are given and checked in the corresponding Teams space

## Course assessment

Assessment Component 1: written examination, Duration: 60 min, Weight: 50 %

Assessment Component 2: Practical assessments, Weight: 50 %

Completion: To pass this module, the examination of each module component must be passed with at least 45%.

## Exam

Test exam: [link](Materials/exam_test.pdf), answers to this exam: [link](Materials/exam_test_answers.pdf)

## Lectures

| Date | Number | Topic | Materials |
| :---: | :---: | --- | --- |
| 05.09.25 | 01 | Introduction to the course. Cross-entropy method (CEM).	| [CEM for optimization](https://people.smp.uq.edu.au/DirkKroese/ps/CEopt.pdf)<br> [Tetris with CEM](https://www.researchgate.net/publication/6743957_Learning_Tetris_Using_the_Noisy_Cross-Entropy_Method)<br> [OpenAI ES](https://openai.com/blog/evolution-strategies/)<br> [Review of evolutionary strategies](https://lilianweng.github.io/lil-log/2019/09/05/evolution-strategies.html)<br> [WANN](https://arxiv.org/pdf/1906.04358.pdf) |
| 12.09.25 | 02 | Bellman equations. Value Iteration, Policy Iteration. | Sutton, Barto, ch.3-4<br> [A (Long) Peek into Reinforcement Learning](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html) |
| 19.09.25 | 03 | Model-free tabular methods: Monte Carlo Control, Temporal Difference (TD), SARSA, Q-learning. | [Slides](http://www.machinelearning.ru/wiki/images/3/34/TD_learning_2021.pdf)<br>Sutton, Barto, ch.5-6<br> [Visualization of TD-learning (distill)](https://distill.pub/2019/paths-perspective-on-value-learning/) |
| 26.09.25 | 04 | Deep Q-Network (DQN) and its modifications. | [Slides](http://www.machinelearning.ru/wiki/images/3/3c/Deep_Q_learning_2021.pdf)<br>[DQN](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)<br>[Double DQN](https://arxiv.org/pdf/1509.06461.pdf)<br>[Prioritized Experience Replay](https://arxiv.org/pdf/1511.05952.pdf)<br>[Noisy Networks](https://arxiv.org/abs/1706.10295)<br>[Dueling DQN](https://arxiv.org/abs/1511.06581)<br> [R2D2](https://openreview.net/pdf?id=r1lyTjAqYX)<br>[Agent57](https://arxiv.org/abs/2003.13350) |
| 10.10.25 | 05 | Distributional RL. Quantile Regression DQN (QR-DQN). | [Categorical DQN](https://arxiv.org/pdf/1707.06887.pdf)<br>[QR-DQN](https://arxiv.org/pdf/1710.10044.pdf) | [Implicit Quantile Networks (IQN)](https://arxiv.org/pdf/1806.06923.pdf)<br>[Rainbow DQN](https://arxiv.org/pdf/1710.02298.pdf) |
| 17.10.25 | 06 | Policy gradient methods: REINFORCE, Advantage Actor-Critic (A2C).	| Sutton, Barto, ch.13<br>[A2C](https://arxiv.org/pdf/1602.01783.pdf)<br> [Review of Policy Gradient algorithms](https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html#what-is-policy-gradient)<br>[A2C comic](https://hackernoon.com/intuitive-rl-intro-to-advantage-actor-critic-a2c-4ff545978752) |
| 24.10.25 | 07 | Trust-Region Policy Optimization (TRPO).	| [TRPO](https://arxiv.org/pdf/1502.05477.pdf) | 
| 07.11.25 | 08 | Proximal Policy Optimization (PPO). Generalized Advantage Estimation (GAE). | [Slides](http://www.machinelearning.ru/wiki/images/1/14/MSU_2021_PPO.pdf)<br>[PPO](https://arxiv.org/pdf/1707.06347.pdf)<br> [Implementation matters in RL](https://arxiv.org/pdf/2005.12729.pdf)<br>[GAE](https://arxiv.org/pdf/1506.02438.pdf)<br> Sutton, Barto, ch.12 |
| 14.11.25 | 09 | Continuous control. Soft Actor Critic (SAC). | [Deep Deterministic Policy Gradient (DDPG)](https://arxiv.org/pdf/1509.02971.pdf)<br>[Twin-Delayed DDPG (TD3)](https://arxiv.org/pdf/1802.09477.pdf)<br>[Soft Actor-Critic (SAC)](https://arxiv.org/pdf/1801.01290.pdf)<br> [Truncated Quantile Critics (TQC)](https://arxiv.org/abs/2005.04269)<br> [RL as probabilistic inference](https://arxiv.org/pdf/1805.00909.pdf) | 
| 21.11.25 | 10 | Multi-armed bandits. Intrinsic motivation.	| [Bandits Algorithms](https://banditalgs.com/)<br> [Slides](http://www.machinelearning.ru/wiki/images/f/fa/Exploration-vs-exploitation.pdf)<br>Sutton, Barto, ch.2<br>[Random Network Distillation (RND)](https://arxiv.org/abs/1810.12894)<br>[Intrinsic Curiosity Module (ICM)](https://arxiv.org/abs/1705.05363)<br> [Exploration Strategies](https://lilianweng.github.io/lil-log/2020/06/07/exploration-strategies-in-deep-reinforcement-learning.html)<br>[Variational Information Maximizing Exploration (VIME)](https://arxiv.org/abs/1605.09674)<br>[Never Give Up (NGU)](https://arxiv.org/abs/2002.06038) |
| 28.11.25 | 11 | Monte Carlo Tree Search. AlphaZero.	| [AlphaZero](https://discovery.ucl.ac.uk/id/eprint/10045895/1/agz_unformatted_nature.pdf) | [AlphaZero in one picture](https://miro.medium.com/max/2000/1*0pn33bETjYOimWjlqDLLNw.png) |
| 05.12.25 | 12 | Linear Quadratic Regulator (LQR). Model-based RL.	| [Slides](http://rail.eecs.berkeley.edu/deeprlcourse/static/slides/lec-10.pdf)<br>[Slides](http://rail.eecs.berkeley.edu/deeprlcourse/static/slides/lec-11.pdf) | [World Models](https://worldmodels.github.io/) |


## Materials
[R.Sutton, A.Barto. Reinforcement Learning: An Introduction, 2018](https://drive.google.com/file/d/1Z4W_-0IaMNpZnhnMkqcDVM_EA79GFJo-/view)

[Unofficial textbook in Russian](https://github.com/FortsAndMills/RL-Theory-book/blob/main/RL_Theory_Book.pdf)

[The Course Deep Reinforcement Learning (CS 285), UC Berkeley](https://www.youtube.com/playlist?list=PLkFD6_40KJIxJMR-j5A1mkxK26gh_qg37)
