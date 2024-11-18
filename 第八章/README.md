# ChannelNet
此案例的源仓库链接 [https://github.com/Mehran-Soltani/ChannelNet](https://github.com/qiongwu86/RIS-RB-AoI-V2X-DRL)

Implementation of the paper "Deep-Reinforcement-Learning-Based AoI-Aware Resource Allocation for RIS-Aided IoV Networks" https://ieeexplore.ieee.org/document/10663259

# Abstract 

Reconfigurable Intelligent Surface (RIS) is a pivotal technology in communication, offering an alternative path that significantly enhances the link quality in wireless communication environments. In this paper, we propose a RIS-assisted internet of vehicles (IoV) network, considering the vehicle-to-everything (V2X) communication method. In addition, in order to improve the timeliness of vehicle-to-infrastructure (V2I) links and the stability of vehicle-to-vehicle (V2V) links, we introduce the age of information (AoI) model and the payload transmission probability model. Therefore, with the objective of minimizing the AoI of V2I links and prioritizing transmission of V2V links payload, we construct this optimization problem as an Markov decision process (MDP) problem in which the BS serves as an agent to allocate resources and control phase-shift for the vehicles using the soft actor-critic (SAC) algorithm, which gradually converges and maintains a high stability. A AoI-aware joint vehicular resource allocation and RIS phase-shift control scheme based on SAC algorithm is proposed and simulation results show that its convergence speed, cumulative reward, AoI performance, and payload transmission probability outperforms those of proximal policy optimization (PPO), deep deterministic policy gradient (DDPG), twin delayed deep deterministic policy gradient (TD3) and stochastic algorithms.

