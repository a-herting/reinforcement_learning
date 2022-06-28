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
 -  Set of states 𝑆

-   Set of actions 𝐴𝑐𝑡𝑖𝑜𝑛𝑠(𝑠)

-   Transition model 𝑃(𝑠′|𝑠,𝑎)

-   Reward function 𝑅(𝑠,𝑎,𝑠′)


***Q-learning Model*** is the method used for learning a function ***Q(s , a)*** which is used to generate/update a table that estimates the value of performing an action ***a*** in state ***s***. 
 -  Set of states 𝑆

-   Set of actions 𝐴𝑐𝑡𝑖𝑜𝑛𝑠(𝑠)

-   Transition model 𝑃(𝑠′|𝑠,𝑎)

-   Reward function 𝑅(𝑠,𝑎,𝑠′)

**Q-learning**
-   Start with **𝑄(𝑠,𝑎) = 0** for all **𝑠,𝑎**
-   Update **𝑄** when we take an action
-   **𝑄(𝑠,𝑎)** = 𝑄(𝑠,𝑎) + 𝛼(reward + 𝛾max(𝑠′,𝑎′) − 𝑄(𝑠,𝑎)) = (1−𝛼)𝑄(𝑠,𝑎) + 𝛼(reward + 𝛾max(𝑠′,𝑎′))

Additional information on reinforcement learning can be [found here](https://towardsdatascience.com/reinforcement-learning-101-e24b50e1d292).
Additional information from the reinforcement course can be [found here](https://www.youtube.com/watch?v=CGP0oV1kcJw&list=PLvMRWNpDTNwQZkB840U2d9JFXcA8spGMF&index=5). 
