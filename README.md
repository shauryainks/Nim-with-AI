

# Nim Game with AI

This project implements the game of Nim, a mathematical strategy game, along with an AI player trained using Q-learning. The AI player learns to play Nim optimally through self-play.

## How to Use

### Prerequisites

- Python 3.x installed

### Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/shauryainks/Nim-with-AI.git
```

2. Navigate to the project directory:

```
cd Nim-with-AI
```

### Training the AI

To train the AI player, run the following command:

```
python nim.py
```

This will train the AI by playing thousands of games against itself using Q-learning.

### Playing the Game

To play the game against the trained AI, run:

```
python play.py
```

Follow the on-screen instructions to make your moves.

## Files

- `nim.py`: Contains the implementation of the Nim game and the Q-learning AI.
- `play.py`: Script to play the game against the trained AI.

## About Nim

Nim is a two-player mathematical game where players take turns removing objects from distinct heaps or piles. The game ends when there are no objects left, and the player who takes the last object loses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
