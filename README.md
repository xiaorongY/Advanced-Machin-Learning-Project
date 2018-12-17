# Advanced Machin Learning Project: DQN and Policy Gradient Models for Pong
The notebook contains codes of the DQN and Policy Gradient Models for Pong game.










The thrid notebook corresponding to Policy Gradient model, which consists of four parts as below.
1. Construct Policy network and define functions for saving and reloading models during training
2. Set up logging directory
3. Set up parameters, which can be further experimented with
4. Training the Policy network and save training results and videos

In order to reproduce similar result under Pong-v0 environment, you just need to run all the kernels sequentially.

In order to reproduce similar result under PongDeterministic-v4 environment, you need to change the line of environment setting to: 

env = gym.make('PongDeterministic-v4')

and run all the kernels sequentially.

The trained agent under original Pong-v0 environmnet receives an average reward of 6 after 2 days of training on a Macbook Pro until 20,000 episodes.
Below is an example of an episode played by our trained agent attaining a score of 6.

![image](https://github.com/xiaorongY/Advanced-Machin-Learning-Project/blob/master/pg_reward%3D6.gif)
