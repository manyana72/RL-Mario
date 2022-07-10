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

# Q- Learning
This is based on the Bellman Optimality Equation, which provides a formulation for estimating the optimal Q values for all state-action pairs. This gives the maximum expected return when we start with a state s and take some action a. 

# Double DQN
We take 2 separate q value tables in this case and 


# Conclusion
I have trained the model first using Deep Q Network, and then enhancing the results by training using a Double DQN. The graphs below illustrate the comparison between the results obtained on using both the methods. For the lack of more training episodes, the values obtained are not that concrete in estabilishing positive training of the model. I have also included the visuals of the trained model playing the game in both versions.
Also, through the journey of this project I was exposed to the various intricacies of Reinforcement Learning, such as different varaints of the same (e.g Policy based, value based RL etc.)
 
