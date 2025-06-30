CS 370 Project Two: Pirate Intelligent Agent
Brief Summary
This project focused on designing and training an intelligent pirate agent using deep Q-learning, a form of reinforcement learning, to navigate a maze and find a treasure before a human player. The agent learns the optimal path to the treasure through trial and error, using neural networks to make decisions based on previous experiences.

Code Overview
Given Code:

treasuremaze.py: Defines the environment (8x8 maze) including movement rules, reward structure, and the visual representation of the game state.

gameexperience.py: Implements experience replay, allowing the agent to remember past states, actions, and rewards for training.

Starter code in the Jupyter Notebook for building the neural network model.

Code I Created:

I implemented the Q-training algorithm in the notebook using:

Experience replay

ε-greedy exploration

Target updates

Model training using Keras

I fine-tuned training parameters (e.g., memory size, batch size, number of epochs) to ensure convergence and achieve a high win rate.


What Do Computer Scientists Do?
Computer scientists develop algorithms, design software systems, and solve real-world problems using computational thinking. In this project, I applied machine learning and AI principles to develop an autonomous agent. This aligns with what computer scientists do in industries like gaming, robotics, and data science—solving complex problems by teaching machines how to learn from data.


My Approach as a Computer Scientist
I approached this problem using a systematic, iterative process:

Understand the domain and rules (maze, rewards, valid moves).

Break the problem down (environment, experience, model, training loop).

Experiment and refine (tuning ε, epochs, reward shaping).

Evaluate performance and visualize results to confirm learning.

This mirrors how professional developers and researchers tackle large-scale problems: breaking them into smaller components and continuously testing and improving.


My Ethical Responsibilities
As a developer working with AI:

I must ensure fairness and safety. Even in a game, ensuring the agent plays fairly and learns efficiently without exploiting loopholes is important.

In broader applications, AI systems must be transparent, accountable, and respectful of user privacy.

I am responsible for avoiding unintended harm, such as reinforcing biased behavior or creating models that make opaque decisions.

These principles apply whether I’m building game agents, recommendation systems, or real-world decision-making tools.
