# Solitaire - Artificial Intelligence Agent

![Solitaire AI](https://i.ibb.co/qYtPF8f/solitaire.png)

## Introduction

The **Solitaire AI Agent** project was undertaken as part of the Artificial Intelligence course. The primary objective of this project is to develop a Python program capable of solving various puzzles of a Solitaire game variant.

## Solitaire Game Variant

This is a single-player game that dates back to the 17th century French court of Louis XIV. The game involves moving marbles on a board with small holes. The goal is to strategically eliminate marbles from the board, leaving only one marble in the center position.

The game's rules include:

- Valid moves involve jumping one marble over an adjacent marble, removing the jumped marble, and landing in an empty hole.
- The objective is to find a sequence of moves that leaves only one marble on the board.

## Problem Description

The project involves solving Solitaire puzzles with varying board dimensions and different numbers of empty spaces. The goal is to determine the sequence of moves that results in leaving a specified number of marbles on the board, fulfilling the requirements.

### Technology Stack

- Python and search algorithms provided were utilized for searching and decision-making processes.

## Testing

The Solitaire AI Agent was tested to make sure it successfully run depth-first search, greedy search, and A* search algorithms for any provided problem. Additionally, the code was tested to be capable of solving the problems mentioned using an informed search approach in less than a minute.

## Getting Started

To run the project follow these steps:

### Prerequisites

Before running the project, ensure you have Python installed on your system. If you don't have Python installed, you can download and install it from the [official Python website](https://www.python.org/downloads/) or use package managers like apt (for Linux) or Homebrew (for macOS):

### Running the Agent

To run the script, follow these steps:

1. Open a terminal window.
2. Navigate to the project directory.
3. Run the `agent.py` script using Python:
   
   ```bash
   python agent.py
   ```

The Solitaire AI Agent project showcases the application of AI algorithms to solve complex puzzles. By implementing various types, modeling the problem, and employing search strategies, the project demonstrates the practical application of artificial intelligence in solving intricate problems. Thank you for exploring the project!
