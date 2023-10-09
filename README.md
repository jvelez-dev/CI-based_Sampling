# CI-based_Sampling

By incorporating causal inference-based sampling into the replay buffer of a DQN, we aim to improve the efficiency and effectiveness of learning in solving the classic control problem. This approach allows us to prioritize experiences that are more likely to have a causal impact on the agent's decision-making process, leading to more targeted and informed learning. In contrast, traditional random sampling in a DQN's replay buffer lacks this prioritization and may result in slower convergence and suboptimal performance. 

## Structure
### CI-Based-DQN
You'll find a Python notebook here detailing an experiment with a DQN's replay buffer and causal inference-based sampling.

### Random-Sampling-DQN
You'll find a Python notebook here detailing an experiment with a DQN's replay buffer and random sampling.
[![DOI](https://zenodo.org/badge/702496492.svg)](https://zenodo.org/badge/latestdoi/702496492)
