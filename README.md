# Reinforcement Learning Project

Given the field below, I used reinforcement learning with Q-learning to find solutions to the field within Jupyter notebook.

![enter image description here](https://github.com/LearnPythonWithRune/MachineLearningWithPython/raw/4c01affa620e139fe8a3f540690e4b72b569bdb0/jupyter/starter/img/field-2.png)

***Reinforcement learning*** is a one of three areas under machine learning that allows the agent to find the path with the maximum amount of reward. 

 1. The environment gives the agent a state. 
 2. The agent takes an action specific to the state (what's possible). 
 3. The environment provides the agent with a state and reward (positive or negative). 
 4. The agent takes an action specific to the state (what's possible). 

Actions are decisions that the agent can learn, while state is useful for helping the agent choose an action. 

***Markov's Decision Process*** is used to create the decision-making model to represent states, actions, and the agent's rewards. 
 -  Set of states ð

-   Set of actions ð´ðð¡ðððð (ð )

-   Transition model ð(ð â²|ð ,ð)

-   Reward function ð(ð ,ð,ð â²)


***Q-learning Model*** is the method used for learning a function ***Q(s , a)*** which is used to generate/update a table that estimates the value of performing an action ***a*** in state ***s***. 
 -  Set of states ð

-   Set of actions ð´ðð¡ðððð (ð )

-   Transition model ð(ð â²|ð ,ð)

-   Reward function ð(ð ,ð,ð â²)

**Q-learning**
-   Start with **ð(ð ,ð) = 0** for all **ð ,ð**
-   Update **ð** when we take an action
-   **ð(ð ,ð)** = ð(ð ,ð) + ð¼(reward + ð¾max(ð â²,ðâ²) â ð(ð ,ð)) = (1âð¼)ð(ð ,ð) + ð¼(reward + ð¾max(ð â²,ðâ²))

Additional information on reinforcement learning can be [found here](https://towardsdatascience.com/reinforcement-learning-101-e24b50e1d292).
Additional information from the reinforcement course can be [found here](https://www.youtube.com/watch?v=CGP0oV1kcJw&list=PLvMRWNpDTNwQZkB840U2d9JFXcA8spGMF&index=5). 
