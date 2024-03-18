# Nim

## Project Description

This project implements an AI player for the game of Nim using the Q-learning algorithm. 
Nim is a two-player game where players take turns removing amounts from distinct heaps. 
Whoever removes the amount before all the piles are empty loses.
The goal of the AI player is to learn optimal strategies for playing Nim through reinforcement learning.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Credit](#credit)
- [License](#license)

## Installation

You'll need to have Python and pip3 installed. You can download them from the [official Python website](https://www.python.org/downloads/).

1. Clone the repository:

```bash
git clone https://github.com/colindao/nim.git
```

2. Navigate to the project directory:

```bash
cd nim
```

3. Install the required dependencies:

```bash
pip3 install -r requirements.txt
```

## Usage

To play against the AI, run the following command:

```bash
python play.py
```

Follow the prompts to make your moves. The AI player will respond with its moves based on the optimal strategy. Good luck!

## Features

**Q-learning**: The AI agent uses the Q-learning algorithm, a type of reinforcement learning, to associate playable moves with rewards such as if it results in a winning position. <br />
<br />
**State Representation**: Design an effective state representation scheme to represent the current state of the game, including the number of piles and their amounts. <br />
<br />
**Action Selection**: Implement a policy for selecting actions (i.e., moves) based on the current state and the learned Q-values. <br />
<br />
**Training and Evaluation**: Train the AI player through repeated gameplay sessions against itself, adjusting Q-values based on observed rewards and penalties.

## Credit

This project was completed as a part of [CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2024/). Go check them out!

## Technologies
**Language**: Python <br />
**Libaries**: Random, Time

## License

MIT License

Copyright (c) 2024 Colin Dao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
