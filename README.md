# dqn_navigation
Udacity Deep reinforcement learning navigation exercise

This project, implements an agent trained to navigate (and collect bananas!) in a large, square world.
A gif showing the navigation and collection of bananas.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

# Files provided in this submission
The following files are included in this repository:
  
README.md         - this readme file.

Navigation.ipynb  - a jupyter notebook containing the code implementation.

Report.ipynb      - a jupyter notebook containing a report of the project.

checkpoint.pth    - the saved model weights of the successful agent.

scores.txt        - a python pickle file containing the scores of the experiment.It's used to create the report.


# Running the code
The code must be run in the Udacity project workspace.
Simply upload Navigation.ipynb to the workspace and run the notebook. 
