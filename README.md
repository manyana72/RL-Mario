# RL-Mario
VLG Summer Project on Reinforcement Learning applied on the game Super Mario

# AIM
The aim of this project is to train an RL Agent to play the game Super Mario, in order to do that, we implement the following strategies:
1. Using a DQN based model in order to maximize reward at each step.
2. Enhancing the current model using Double DQN.

Comparing the output (i.e the maximum reward produced in each case)


# THEORY
SUPER MARIO
The goal of the game is to reach the rightmost end of the level as quickly as possible. To do this our agent (Mario) can be moved using controls (taking action a with every movement). We obtain rewards based on the most benefit(most rightward movement) that our agent can receive while taking an action. The states in our environment are the game image frames (taken 5 at a time, grayscaled and reduced to appropriate pixel dimensions and stacked together)

# Q Learning
This method assumes that we have the rewards associated with each state at our dispense, and we then choose the maximum reward/ choose a random path sometimes in order to build a robust learning model. The Q values (Action Values) are updated in order to obtain max Q value from the successive state. 

# DQN
This is based on the Bellman Optimality Equation, which provides a formulation for estimating the optimal Q values for all state-action pairs. This gives the maximum expected return when we start with a state s and take some action a. 

![image](https://user-images.githubusercontent.com/99553025/178161891-5ea3e278-aaae-4031-8e83-cddb751fa4dc.png)


# Double DQN
We take 2 separate q value tables in this case and they are updated alternately. In order to update estimator 1, the Q value for the next step is evaluated using estimator 2. 


# Conclusion
I have trained the model first using Deep Q Network, and then enhancing the results by training using a Double DQN. The graphs below illustrate the comparison between the results obtained on using both the methods. For the lack of more training episodes, the values obtained are not that concrete in estabilishing positive training of the model. I have also included the visuals of the trained model playing the game, trained by the model using DoubleDQN .


![image](https://user-images.githubusercontent.com/99553025/178161873-e8201bfe-3b0d-46ab-97d9-18481e214684.png)


Also, through the journey of this project I was exposed to the various intricacies of Reinforcement Learning, such as different varaints of the same (e.g Policy based, value based RL etc.)
 
