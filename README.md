# ANLY591-Group4-Traffic-Simulation

Group 4: Shiwei Yu, Xiaomeng Chen

Traffic Simulation and navigation is a popular issue in reinforcement learning that involves simulating traffic scenarios and training agents to navigate in these scenarios. The environment models the behavior of vehicles, and then the agent learns to take actions that maximize the reward or minimize penalties, such as optimizing travel time, reducing accidents or delays, and ensuring safety.  

This project intends to apply three RL algorithms for discrete action spaces on specific traffic environments designed by OpenAI, including highway env and intersection env. Finally all three models are evaluated and compared in terms of effectiveness and drawbacks in this context. 


 - Proximal Policy Optimization (PPO)
 - DQN
 - Actor-Critic (A2C)
 
 And finally we obtained the following summary table -- 
 
|  	| PPO 	| DQN 	| DQN  	| Actor-Critic (A2C) 	|
|---	|:---:	|:---:	|:---:	|:---:	|
| Cumulative rewards 	| 18388.01 	| 54037.98 	| 423.26 	| 371.72 	|
| Mean rewards 	| 21.17 	| 9.55 	| 4.86 	| 4.37 	|
| Std rewards 	| 0.62 	| 5.07 	| 4.82 	| 4.89 	|
