# Deep-Reinforcement-Learning-with-Double-Q-learning-DDRQN-
####### Recent developments in reinforcement learning for first person shooter (FPS) games have shown great promise
and novelty in handling the complex required tasks. We trained a reinforcement learning agent in platform ViZDoom, 
to play the game Doom. Previous work proved the efficacy of Deep Recurrent Q-Networks in handling Partially Observable 
Markov Decision Processes (POMDP) and for Doom in particular. Subsequent research identified the upward bias of Q-values 
by single Q-networks due to the same Q-function selecting an action and evaluating its worth. A technique called Double 
Q-Learning was shown to remedy the problem by using two Q-functions and decoupling the selection and evaluation of the action. 
Our proposed model synthesizes a Double Q-Network and a Deep Recurrent Q-Network, to implement a Double Deep Recurrent Q-Network (DDRQN).
We compare our model to a single Deep Recurrent Q-Network where the agent is required to defend the center of the environment until either 
the agent’s health is exhausted, or time runs out.
