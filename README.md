# Reinforcement-learning

## Survey
- [Deep reinforcement learning in computer vision: a comprehensive survey, N Le, VS Rathour, K Yamazaki, K Luu, Artificial Intelligence Review, 2021](https://link.springer.com/article/10.1007/s10462-021-10061-9)
- A Survey on Deep Reinforcement Learning Algorithms for Robotic Manipulation
- [Automatic Curriculum Learning For Deep RL: A Short Survey, arxiv, 2020](https://arxiv.org/abs/1710.06537)

# Reinforcement Learning
# RL Algorithm
[Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor, arxiv, 2018](https://arxiv.org/abs/1801.01290)

# Single-Agent
## Model-Based
[Dream to Control: Learning Behaviors by Latent Imagination, arxiv, 2019](https://arxiv.org/abs/1912.01603)

## forward dynamics
[Sample-efficient Reinforcement Learning Representation Learning with Curiosity Contrastive Forward Dynamics Model, arxiv, 2021](https://arxiv.org/abs/2103.08255)

## Contrastive Learning
[CURL: Contrastive Unsupervised Representations for Reinforcement Learning, PMLR, 2020](http://proceedings.mlr.press/v119/laskin20a.html)

## Offline RL
[Conservative Q-Learning for Offline Reinforcement Learning, NeurIPS, 2020](https://proceedings.neurips.cc/paper/2020/hash/0d2b2061826a5df3221116a5085a6052-Abstract.html)

[A Minimalist Approach to Offline Reinforcement Learning, Arxiv, 2021](https://arxiv.org/abs/2106.06860)

IQL : [Believe What You See: Implicit Constraint Approach for Offline Multi-Agent Reinforcement Learning, NeurIPS, 2021](https://proceedings.neurips.cc/paper/2021/hash/550a141f12de6341fba65b0ad0433500-Abstract.html)

### Distribution correction

DiCE : [The DIstribution Correction Estimation Library](https://github.com/google-research/dice_rl)

OptiDiCE : [Offline Policy Optimization via Stationary Distribution Correction Estimation, ICML, 2021](https://github.com/secury/optidice)

AW : [Harnessing Mixed Offline Reinforcement Learning Datasets via Trajectory Weighting, ICLR, 2023 under review]([https://openreview.net/pdf?id=OhUAblg27z](https://github.com/Improbable-AI/harness-offline-rl))
DW : [Beyond Uniform Sampling: Offline Reinforcement Learning with Imbalanced Datasets, NeurIPS, 2023](https://github.com/Improbable-AI/dw-offline-rl)


## Passive data
ICVF : [Reinforcement Learning from Passive Data via Latent Intentions, PMLR, 2023](https://proceedings.mlr.press/v202/ghosh23a.html)

V-PTR : [Robotic Offline RL from Internet Videos via Value-Function Pre-Training, Arxiv, 2023](https://arxiv.org/abs/2309.13041)

## Hierarchical RL
HAC : [Learning Multi-Level Hierarchies with Hindsight, Arxiv, 2019](https://arxiv.org/abs/1712.00948)

HIRO : [Data-Efficient Hierarchical Reinforcement Learning, NeurIPS, 2018](https://proceedings.neurips.cc/paper/2018/hash/e6384711491713d29bc63fc5eeb5ba4f-Abstract.html)

HIGL : [Landmark-Guided Subgoal Generation in Hierarchical Reinforcement Learning, Arxiv, 2021](https://arxiv.org/abs/2110.13625)

HIQL : [Offline Goal-Conditioned RL with Latent States as Actions, Arxiv, 2023](https://arxiv.org/abs/2307.11949)

WGCSL : [Weighted Goal-conditioned Supervised Learning, ICLR, 2022](https://sites.google.com/view/wgcsl/)

Guide to Control : [Offine Hierarchical Reinforcement Learning Using Subgoal Generation for Long-Horizon and Sparse-Reward Tasks, IJCAI, 2023](https://www.ijcai.org/proceedings/2023/0469.pdf)

## Graph-guided RL
L3P : [World Model as a Graph: Learning Latent Landmarks for Planning, ICML, 2021](https://github.com/LunjunZhang/world-model-as-a-graph)

DHRL : [A Graph-Based Approach for Long-Horizon and Sparse Hierarchical Reinforcement Learning, NeurIPS, 2022](https://github.com/jayLEE0301/dhrl_official)

VMG (offline) : [Value Memory Graph: A Graph-Structured World Model for Offline Reinforcement Learning, ICLR,2023](https://github.com/TsuTikgiau/ValueMemoryGraph)

## Multi-modal
- Multimodal Knowledge Alignment with Reinforcement Learning
- Multimodal Reinforcement Learning for Robots Collaborating with Humans

## Navigation 
- Vision-and-Language Navigation: Interpreting visually-grounded navigation in structions in real environments
- Exploiting Multi-Modal Fusion for Urban Autonomous Driving Using Latent Deep Reinforcement Learning
- Semantic Audio-Visual Navigation

## Planning 
- A deep reinforcement learning based method for real-time path planning and dynamic obstacle avoidance

## multi reward 
- Multimodal Reward Shaping for Efficient Exploration in Reinforcement Learning

  
# Multi-Agent
## RL Algorithm

## Sequential Modeling (Transformer)
Decision Transformer : [ Reinforcement Learning via Sequence Modeling, NeurIPS, 2021](https://proceedings.neurips.cc/paper_files/paper/2021/hash/7f489f642a0ddb10272b5c31057f0663-Abstract.html)

MAT : [Multi-Agent Reinforcement Learning is a Sequence Modeling Problem, NeurIPS, 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/69413f87e5a34897cd010ca698097d0a-Abstract-Conference.html)

## Model-Based
MBVD : [Mingling Foresight with Imagination: Model-Based Cooperative Multi-Agent Reinforcement Learning, NeurIPS, 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/49be51578b507f37cd8b5fad379af183-Abstract-Conference.html)

## Q learning
Value Decomposition : [Value-Decomposition Networks For Cooperative Multi-Agent Learning, arxiv 2017](https://arxiv.org/abs/1706.05296)

QMIX : [Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning, arxiv, 2018](https://arxiv.org/abs/1803.11485)

## Policy gradient
MAPPO : [The Surprising Effectiveness of PPO in Cooperative, Multi-Agent Games, arxiv, 2021](https://arxiv.org/abs/2103.01955)

HAPPO : [Trust Region Policy Optimisation in Multi-Agent Reinforcement Learning, arxiv, 2022](https://arxiv.org/abs/2109.11251)

## Offline learning
OMAR : [Plan Better Amid Conservatism: Offline Multi-Agent Reinforcement Learning with Actor Rectification, NeurIPS, 2022](https://proceedings.mlr.press/v162/pan22a.html)

## Hierarchical method
ODIS : [Discovering generalizable multi-agent coordination skills from multi-task offline data, ICLR(openreview), 2023](https://openreview.net/forum?id=53FyUAdP7d)

HAVEN : [HAVEN: hierarchical cooperative multi-agent reinforcement learning with dual coordination mechanism, AAAI, 2023](https://ojs.aaai.org/index.php/AAAI/article/view/26386)

HiMacMic : [Hierarchical Multi-Agent Deep Reinforcement Learning with Dynamic Asynchronous Macro Strategy, KDD, 2023](https://dl.acm.org/doi/abs/10.1145/3580305.3599379?casa_token=AcvJYLeQwukAAAAA:xKkQ01-M-p2H1WKwbVgF1TXKpRG15KO4S3X8jyOkD4iqcZ5MXWMobRQ_LE87txPulQrfQarc_XU)


## Program-guided
E-MAPP : [Efficient Multi-Agent Reinforcement Learning with Parallel Program Guidance, NeruIPS, 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/4f2accafe6fa355624f3ee42207cc7b8-Abstract-Conference.html)

ProTo: [Program-Guided Transformer for Program-Guided Tasks, NeurIPS, 2021](https://proceedings.neurips.cc/paper_files/paper/2021/hash/8d34201a5b85900908db6cae92723617-Abstract.html)

[Program Guided Agent, ICLR(openreivew), 2022](https://openreview.net/forum?id=BkxUvnEYDH)


## Environment
  ### Multi modal
  - SoundSpaces 2.0: A Simulation Platform for Visual-Acoustic Learning
  - SoundSpaces Challenge @ CVPR 2023 Embodied AI Workshop
  
  ### Offline 
  - D4RL

  ### Imbalanced Offline 
  - 

  ### Multi Agent
  - SMAC
  - SMAC v2
  - Google Research Football
  - Overcooked
  - Multi agetn MuJoCo
  - Multi Particle Environment

  
# Generative model
[Auto-Encoding Variational Bayes, arxiv, 2022](https://arxiv.org/abs/1312.6114)

# Multi-modal
## Representation learning
[Learning Multimodal Rewards from Rankings, V Myers, E Biyik, N Anari, PMRL, 2022](https://proceedings.mlr.press/v164/myers22a.html)

## Missing modality
- [Are Multimodal Transformers Robust to Missing Modality?, M Ma, J Ren, L Zhao, D Testuggine, CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Ma_Are_Multimodal_Transformers_Robust_to_Missing_Modality_CVPR_2022_paper.html)


