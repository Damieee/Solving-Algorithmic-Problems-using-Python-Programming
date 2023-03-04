## Solving Algorithmic Problems using Python Programming

This project implements a scoring system for a baseball game that has rules highlighted below (## Usage), where the scores of past rounds can affect future rounds' scores. The game consists of several rounds, and at the beginning of the game, you start with an empty record.

## Benefits

By completing this Python project, you will learn how to solve algorithmic problems using Python programming language. Specifically, you will learn how to use stacks to maintain a record of scores for a baseball game, and apply various rules to update and manipulate the scores. You will practice writing clean and efficient code, and learn how to break down a problem into smaller parts to come up with a working solution. This project will also help you improve your problem-solving skills and teach you how to test and debug your code effectively. Overall, this project will provide you with practical experience in Python programming and help you build a strong foundation for your future Python projects.

## Installation

Clone the repository to your local machine:
git clone https://github.com/Damieee/Solving-Algorithmic-Problems-using-Python-Programming.git

## Usage

To use the program, pass a list of strings ops to the baseball_game() function. The ops list contains the following operations:

# An integer x - Record a new score of x

# + - Record a new score that is the sum of the previous two scores. It is guaranteed there will always be two previous scores.

# D - Record a new score that is double the previous score. It is guaranteed there will always be a previous score.

# C - Invalidate the previous score, removing it from the record. It is guaranteed there will always be a previous score.

## Your task

Your task is to complete the code in the baseball_game() function by filling in the code block below the comment that says "Write your code here". In this block, you will need to implement the game rules for each operation and update the stack accordingly. After each operation, you should print out the current state of the stack to make sure your code is working correctly.
After completing the code, remove the pass statement and test your implementation by passing different ops lists to the baseball_game() function. 

## Hint

In order to complete the code in the main.py file, you should use conditional statements within the existing for loop. These statements should check each element in the ops list and implement the corresponding action based on the element's representation.

> If the element is an integer, you should append it to the stack list. 

> If it is a "C", you should remove the last element from the stack list (using the appropriate Python list method). 

> If it is a "D", you should double the last element in the stack list and append the result to the stack list. 

> Finally, if the element is a "+", you should add the last two elements in the stack list, and append the result to the stack list.

Use the above hints to complete the "Write your code here" section of the code in the main.py file. Once you have written your code, run the test case and check if the output matches the expected output. If it does not, debug your code and try again until the test case passes. Good luck!
