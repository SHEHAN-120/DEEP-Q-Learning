# 🚀 Lunar Lander AI Agent using OpenAI Gym & PyTorch

This project implements an AI agent to solve the classic **Lunar Lander** environment provided by **OpenAI Gym**. The goal of this environment is to land a spacecraft gently on a designated landing pad using discrete control actions.

## 📚 Project Overview

This project showcases my hands-on application of reinforcement learning techniques to train an AI agent capable of controlling a simulated lunar lander. Using tools like OpenAI Gym and PyTorch, I developed a deep learning model that learns to make intelligent decisions through interaction with the environment.

## 🔧 Technologies & Libraries Used

- Python
- Gymnasium (OpenAI Gym fork) – For the Lunar Lander environment
- PyTorch – For building and training the neural network
- NumPy – For numerical operations
- Google Colab – For running and experimenting with code

## 🧠 What I Learned

- Core concepts of Reinforcement Learning (RL) and reward-based learning
- Implementation of Deep Q-Learning (DQN) using PyTorch
- Use of experience replay, epsilon-greedy strategy, and target networks

## ⚙️ Steps to Run

### 1. Installing the required packages and importing the libraries
- Installing Gymnasium
- Importing the necessary Python libraries

### 2. Building the AI
- Creating the architecture of the Neural Network using PyTorch

### 3. Training the AI
- Setting up the Lunar Lander environment
- Initializing the hyperparameters (learning rate, gamma, epsilon, etc.)
- Implementing Experience Replay to store past experiences
- Creating the Deep Q-Network (DQN) class
- Initializing the DQN agent
- Training the agent using Q-learning and replay memory

### 4. Optional - Visualizing the Results
- Plotting rewards over episodes
- Running the trained agent in the environment to watch performance

## 🚧 Challenges Faced

- Balancing exploration vs. exploitation with a decaying epsilon
- Stabilizing learning using a target network
- Avoiding overfitting during limited training episodes
- Finding optimal hyperparameters like learning rate and gamma

## ✅ Results & Conclusion

After training, the AI agent was able to consistently land safely, achieving an average reward above the environment’s success threshold.

This project strengthened my skills in:
- Deep reinforcement learning
- Model building with PyTorch
- Training analysis and performance optimization


