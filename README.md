# Reinforcement Learning

The goal in this project was to create an RL network that can balance pole in the CartPole game for 400 frames.

Two approaches were taken to solve the problem:

- Using Q-Learning led to relatively quicker results, but in spite of much experimentation with hyperparameters, the cart pole was barely able to stay balanced for more than 100 steps in some of the 20,000 episodes used for training

- On the other hand, using Deep Q-Learning took much longer to produce results, but the objective was achieved: the cart pole stayed balance for 400 steps in many of the 600 episodes used for training
