# Reinforcement-Learning-2048

Reinforcement Learning (RL) is a type of learning mechanism in which an agent learns by completing tasks that are rewarded. It's employed in situations where there's no single right way to tackle a problem (Kaundinya, et al., 2018). Reinforcement learning has been frequently used in recent years to play a variety of strategy games containing uncertainty, such as backgammon, card games, and go. In 2016, AlphaGo consistently defeated world champion Jie Ke in the game of Go, proving that reinforcement learning may achieve superhuman competence in strategy games without prior human experience (Li & Peng, 2021). This latest achievement is seen as a significant advancement in artificial intelligence because the system must explore over a vast state space before making a decision (Amar & Dedieu, 2017).

I chose to work on 2048, a single-player sliding block puzzle game played on a 4x4 grid with each cell a power of 2, which was released in March 2014. The goal of the game is to get a score of 2048 by shifting the grid in any of the four directions (up, down, right, left) and merging two consecutive cells with the same value (Amar & Dedieu, 2017). After attaining the goal, though, the game can be continued by generating tiles with greater numbers. The goal of this project is to create a self-learning agent that can play the game and attain the 2048 goal using Reinforcement Learning. Because of its simplicity and ease of testing Reinforcement Learning agents, 2048 has been a playground for AI researchers since its release. Despite the fact that several studies have been conducted on this game, they all differ in terms of the RL model utilized and the reward function used to train the agent 

In this project, I chose to implement Deep Q-Learning Networks (DQN) and study the influence of reward function choices on agent performance.


![ElegantSaneKingbird-size_restricted](https://user-images.githubusercontent.com/29721075/163733881-75ce4e51-33a0-4855-a4b8-a9670a693cbc.gif)
