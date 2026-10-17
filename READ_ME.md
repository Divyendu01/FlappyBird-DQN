# Flappy Bird AI using Deep Q-Network (DQN)

A deep reinforcement learning project that trains an AI agent to play Flappy Bird using Deep Q-Networks (DQN).

## Approach

- Create and interact with the Flappy Bird environment using Gymnasium
- Use a neural network to estimate Q-values for available actions
- Apply experience replay to train on randomly sampled past experiences
- Use policy and target networks to improve training stability
- Apply an epsilon-greedy strategy to balance exploration and exploitation

## Environment

The project uses the `FlappyBird-v0` environment from `flappy_bird_gymnasium`. It also includes a manual gameplay script for testing the environment with keyboard controls.

## Tech Stack

Python · PyTorch · Gymnasium · flappy-bird-gymnasium · Pygame · PyYAML

## Run

Install the required packages:

```bash
pip install torch gymnasium flappy-bird-gymnasium pygame pyyaml
```

Train the DQN agent:

```bash
python agent.py flappybirdv0 --train
```

Run the trained agent:

```bash
python agent.py flappybirdv0
```

To play manually, run:

```bash
python game_flappy_bird.py
```

Press **Space** to flap and close the game window to exit manual gameplay.

## Author

**Divyendu Sharma**