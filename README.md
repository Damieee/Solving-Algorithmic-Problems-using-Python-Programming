## Baseball Game

This project implements a scoring system for a baseball game that has rules highlighted below (## Usage), where the scores of past rounds can affect future rounds' scores. The game consists of several rounds, and at the beginning of the game, you start with an empty record.

## Benefits

By completing this Python project, you will learn how to solve algorithmic problems using Python programming language. Specifically, you will learn how to use stacks to maintain a record of scores for a baseball game, and apply various rules to update and manipulate the scores. You will practice writing clean and efficient code, and learn how to break down a problem into smaller parts to come up with a working solution. This project will also help you improve your problem-solving skills and teach you how to test and debug your code effectively. Overall, this project will provide you with practical experience in Python programming and help you build a strong foundation for your future Python projects.

## Installation

Clone the repository to your local machine:
git clone https://github.com/Damieee/baseball-game.git

## Usage

To use the program, pass a list of strings ops to the baseball_game() function. The ops list contains the following operations:

# An integer x - Record a new score of x

# + - Record a new score that is the sum of the previous two scores. It is guaranteed there will always be two previous scores.

# D - Record a new score that is double the previous score. It is guaranteed there will always be a previous score.

# C - Invalidate the previous score, removing it from the record. It is guaranteed there will always be a previous score.

## Your task

Your task is to complete the code in the main.py file and remove the "pass" function so your code will be tested appropraitely.