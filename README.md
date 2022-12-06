# RL in Action
---

RL in action is a project-first approach to learning classical and modern reinforcement learning from the basics. 

The [first course][1] in the series is an introduction to the basics of reinforcement learning, where learners build their own 
environment that we call `Foolsball` and use it to train an RL agent to play the game of `Foolsball`. 

![Foolsball screenshot](https://github.com/KnowchowHQ/rl-in-action/raw/master/C1-RL-Intro/W1S2/res/foolsball.png)


### Course 1: Introduction to RL
- Week 1
  - Session 1: Implelement a trial-and-error algorithm for driving a car around a track and understand how an RL algorithm can learn to do the same.
    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W1S1/car_track.ipynb)
    - [Slides](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W1S1/W1S1.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W1S1/car_track.ipynb)
    
  - Session 2: Build a small game, `Foosball`, similar to Football and with an [OpenAI Gym][3] like interface, 
and interact with it to understand the basic terminology of RL: `states`, `actions` and `rewards`.
    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W1S2/foolsball.ipynb)
    - [Slides](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W1S2/W1S2.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W1S2/foolsball.ipynb)
    
    
- Week 2
  - Session 1: Learn to play `Foolsball` using a table-based decision-making algorithm that is populated using dynamic programming(DP). 
Understnad why DP solutions are not feasible and devise an experience-based alternative. Understnad the concepts of `returns` and `policies`.
    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W2S1/foolsball.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W2S1/foolsball.ipynb)
    
   - Session 2: Implement experience-based update of the decision tables by simulating a large number of gameplay `episodes` and Monte Carlo
estimation.  
     - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W2S2/foolsball.ipynb)
     - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W2S2/foolsball.ipynb)
 
 
- Week 3
  - Session 1: Implement improvements that blend learning from new epsiodes with historical knowledge. Understand the explorartion-exploitation dilemma.

    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W3S1/foolsball.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W3S1/foolsball.ipynb)
    
   - Session 2: Implement well-known algorithms: `SARSA`, `Q-Learning` 
     - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W3S2/foolsball.ipynb)
     - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W3S2/foolsball.ipynb)
    
    
- Week 4
  - Session 1: Implement Expected `SARSA` and temporal diffrence `TD` learning algorithms. 
    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W4S1/foolsball-v2.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W4S1/foolsball-v2.ipynb)
    
   - Session 2: Add complexity to the game by making opponents dynamic and test `Q-learning`, `SARSA` and `TD-learning` again.
    - [Starter Code](https://github.com/KnowchowHQ/rl-in-action/blob/master/C1-RL-Intro/W4S2/foolsball-v3.ipynb)
    - [Solution Code](https://github.com/KnowchowHQ/rl-in-action/blob/solution/C1-RL-Intro/W4S2/foolsball-v3.ipynb)
    


### Course 2: Value-based Methods for RL

### Course 3: Policy-based Methods for RL



[1]: https://github.com/KnowchowHQ/rl-in-action/tree/master/C1-RL-Intro
[2]: https://github.com/KnowchowHQ/rl-in-action/raw/master/C1-RL-Intro/W1S2/res/foolsball.png
[3]: https://github.com/openai/gym
