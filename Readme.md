# AI Snake Game using Deep Q-Learning

This project is a reinforcement learning-based Snake game implemented in Python using PyTorch. An AI agent learns to play the classic Snake game using the Deep Q-Learning algorithm (DQN).

## Features

- AI trained using Deep Q-Learning
- Real-time game visualization with Pygame
- Live plotting of scores with Matplotlib
- Save/load model weights
- Adjustable game speed and grid size

## Technologies Used

- Python
- PyTorch
- Pygame
- Matplotlib

## Project Structure

├──agent.py # Main training logic and agent behavior
├── game.py # Snake game environment
├── helper.py # Real-time plotter for training scores
├── model.py # Deep Q-Learning neural network & trainer class
├── model/
│ └── model.pth # Trained model weights
├── assets/
│ └── arial.ttf # Font used in the game UI
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .gitignore # Files to ignore in version control
