# Reinforcement Learning: Snake Game AI

## 📚 Overview

This project utilizes **Reinforcement Learning** with **PyTorch** to train an AI agent to play the classic Snake game using a **Linear Q-Network** model. The objective is to enable the AI to make optimal decisions during gameplay by learning from its experiences.

## 🛠 Files and Functionality

- **snake.py**: Contains the implementation of the Snake game, including game logic and mechanics.
- **agent.py**: Responsible for initiating the training process of the Q-Network model to predict the action the agent should take at each step.
- **agent_trained.py**: Loads and runs the best-trained model to play the Snake game.

## 🚀 How to Run

1. Clone the repository and install the required dependencies:
   ```bash
   git clone [repository URL]
   pip install -r requirements.txt
   ```

2. To train the AI agent, run:
   ```bash
   python agent.py
   ```

3. After training, run the best model with:
   ```bash
   python agent_trained.py
   ```

## 📂 Project Structure

```
├── snake.py               # Implementation of the Snake game
├── agent.py               # Training script for the Q-Network
├── agent_trained.py       # Script to run the trained model
└── README.md              # Project description
```

## 📝 Future Improvements

- Experiment with different neural network architectures for better performance.
- Implement more advanced reinforcement learning techniques (e.g., Double Q-Learning, Dueling DQN).

```
