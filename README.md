# OCRL_Hierarchical_Reinforcement_Learning_Paper_List

## APPROACHES FOR HIERARCHICAL REINFORCEMENT LEARNING

![1](taxonomy_HRL_approaches.png)
by [Hierarchical Reinforcement Learning: A Comprehensive Survey](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/Hierarchical_Reinforcement_Learning:%20A_Comprehensive_Survey.pdf)

* Approaches with subtask discovery or without it. 
* Approaches for training single agent or multiple agents. 
* Approaches for learning on single task or multiple tasks.

1. Single agent, single task, without subtask discovery: The approaches in this division are
grouped into a major class called *Learning Hierarchical Policy* **(LHP)**. The LHP approaches
address the challenge of learning the hierarchical policy π hierarchy of an HRL agent with-
out concerning with subtask discovery. They use handcrafted subtasks.
2. Single agent, single task, with subtask discovery: The approaches in this division are
grouped into two major classes. The first class is called *Learning Hierarchical Policy in
Unification with Subtask Discovery* **(UNI)**. The UNI approaches address the challenge of
learning the subtask space Ω hier ar chy and the hierarchical policy π hier ar chy in a unified
or end-to-end manner. The second class is called *Independent Subtask Discovery* **(ISD)**.
The approaches in this class address the challenge of discovering task-agnostic subtasks
independently from any specific task. The subtask discovery is usually performed in a
pre-training stage and then the subtasks are used to learn HRL agents on downstream
tasks.
3. Multiple agent, single task, without subtask discovery.
4. Multiple agent, single task, with subtask discovery. The approaches in divisions 3 and 4
are grouped into one class called *Multi-Agent HRL* **(MAHRL)**. The MAHRL approaches
broadly address the challenge of learning to coordinate among multiple HRL agents on a
single joint task.
5. Single agent, multiple tasks, without subtask discovery.
6. Single agent, multiple tasks, with subtask discovery. The approaches in divisions 5 and 6
are grouped into one class called *Transfer learning with HRL* **(TransferHRL)**. The Trans-
ferHRL approaches broadly address the challenge of learning to transfer the hierarchical
policy, subtasks, or other knowledge of an HRL agent across multiple tasks, where the
subtasks may be handcrafted or discovered from scratch on multiple tasks.


## Paper List Draft
![1](taxonomy_HRL_approaches.png)

[Dec 6 2021] [Hierarchical Reinforcement Learning with Timed Subgoals (HiTS)](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/Hierarchical_Reinforcement_Learning_With_Timed_Subgoals.pdf)   + [Video](https://www.youtube.com/watch?v=JkPaI3uZU6c)



[Oct 2021] [Detect, Understand, Act: A Neuro-Symbolic Hierarchical Reinforcement Learning Framework](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/A_Neuro-Symbolic_Hierarchical_Reinforcement_Learning_Framework.pdf) +  [Video](https://www.youtube.com/watch?v=1gsLt-zFXiY)

[Jul 2019] [Learning World Graphs to Accelerate Hierarchical Reinforcement Learning](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/Learning_World_Graphs_to_Accelerate_Hierarchical_Reinforcement_Learning.pdf) + [Video](https://www.youtube.com/watch?v=Qk4lJdp7ZAs)

[Nov 2019] [Hierarchical Reinforcement Learning Method for Autonomous Vehicle Behavior Planning](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/Hierarchical_Reinforcement_Learning_Method_for_Autonomous_Vehicle_Behavior_Planning.pdf) + [Video](https://www.youtube.com/watch?v=I4KGeYYyP4g)

[IEEE ITSC 2021] [Trajectory Planning for Autonomous Vehicles Using Hierarchical Reinforcement Learning](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/Trajectory_Planning_for_Autonomous_Vehicles_Using_Hierarchical_Reinforcement_Learning.pdf) +   [Video](https://www.youtube.com/watch?v=R5nWhzCBLFs)

### LHP
[NeurIPS 2018] [cited by 466] [Data-Efficient Hierarchical Reinforcement Learning (Google)](https://github.com/SiyiDai/OCRL_Hierarchical_Reinforcement_Learning_Paper_List/blob/master/NeurIPS-2018-data-efficient-hierarchical-reinforcement-learning-Paper.pdf) + [Video](https://www.youtube.com/watch?v=VetQHnyiRrI)
### UNI
#### Unified Learning of Policy Tree
[2016] [cited by 103] [Probabilistic inference for determining options in reinforcement learning](https://link.springer.com/article/10.1007/s10994-016-5580-x) 

[NIPS 2009] [cited by 279] [Skill discovery in continuous reinforcement learning domains using skill chaining](https://proceedings.neurips.cc/paper/2009/hash/e0cf1f47118daebc5b16269099ad7347-Abstract.html)

[AAAI 2017] **[cited by 766]** [The Option-Critic Architecture](https://ojs.aaai.org/index.php/AAAI/article/view/10916) + [Video](https://www.youtube.com/watch?v=xVkh5-aIvpg)

[2017] [cited by 35] [Learnings options end-to-end for continuous action tasks](https://arxiv.org/abs/1712.00004)

[NeurIPS 2018] [cited by 51] [Learning abstract options](https://proceedings.neurips.cc/paper/2018/hash/cdf28f8b7d14ab02d12a2329d71e4079-Abstract.html)

[NeurIPS 2019] [cited by 22] [DAC: The Double Actor-Critic Architecture for Learning Options](https://proceedings.neurips.cc/paper/2019/hash/4f284803bd0966cc24fa8683a34afc6e-Abstract.html)

#### Unified Learning of Feudal Hierarchy

[2017] **[cited by 657]** [FeUdal networks for hierarchical reinforcement learning](http://proceedings.mlr.press/v70/vezhnevets17a/vezhnevets17a.pdf) + [Video(en)](https://www.youtube.com/watch?v=DLVjU75x0WQ) + [Video(zh)](https://www.youtube.com/watch?v=uVTbqat92Ps)

[ICLR 2019] [cited by 120] [Near-Optimal Representation Learning for Hierarchical Reinforcement Learning](https://arxiv.org/abs/1810.01257)

### ISD
[PMLR 2018] **[cited by 99]** [Self-Consistent Trajectory Autoencoder: Hierarchical RL with Trajectory Embeddings](http://proceedings.mlr.press/v80/co-reyes18a/co-reyes18a.pdf)+ [Video](https://www.youtube.com/watch?v=2mw1tcbz19g)
### Multi-task domain 
[cs.LG 2020] [cited by 163] [Dynamics-Aware Unsupervised Discovery of Skills](https://arxiv.org/abs/1907.01657) + [Video](https://www.youtube.com/watch?v=HYEzHX6-fIA)