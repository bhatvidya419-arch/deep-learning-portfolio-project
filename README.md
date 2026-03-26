# deep-learning-portfolio-project


RL Game Agent: CartPole DQN
This project implements a Deep Q-Learning (DQN) agent to solve the classic CartPole control problem using PyTorch and Gymnasium.

📖 Problem Definition
The goal is to train an agent to balance a pole on a moving cart by applying forces (left or right). The agent must learn to keep the pole upright for as long as possible (max 500 steps).

🛠️ Setup & Installation
Prerequisites
Python 3.8+
pip
Installation
Clone the repository and install the required packages:

git clone https://github.com/YOUR_USERNAME/deep-learning-portfolio-project.gitcd deep-learning-portfolio-projectpip install -r requirements.txt
🚀 Usage
To train the agent from scratch:

bash

python train.py
To run a demo with the pre-trained model:

bash

python app.py
📊 Results
The agent successfully solves the environment (achieving an average score of 495+ over 100 episodes) within 300 training episodes.

Training Rewards Plot

🧠 Model Architecture
Input Layer: 4 neurons (State dimensions)
Hidden Layers: 2 Linear layers (128 units) with ReLU activation
Output Layer: 2 neurons (Actions: Left, Right)
🔮 Future Improvements
Implement Double DQN to reduce overestimation bias.
Add Dueling Network architecture for better state-value estimation.
Use Convolutional Neural Networks (CNNs) to learn from raw pixel inputs
