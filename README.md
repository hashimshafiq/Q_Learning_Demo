# Q Learning

This is simple example of of a type of [reinforcement learning] (https://en.wikipedia.org/wiki/Reinforcement_learning) called [Q Learning](https://en.wikipedia.org/wiki/Q-learning)

## Overview

● Rules: The agent (yellow box) has to reach one of the goals to end the game (green or red cell).

● Rewards: Each step gives a negative reward of -0.04. The red cell gives a negative reward of -1. The green one gives a positive reward of +1.

● States: Each cell is a state the agent can be.

● Actions: There are only 4 actions. Up, Down, Right, Left.

## Dependencies

-Python 3.5

-tkinter

If on Ubuntu you can install tkinter for python3.5 with

$sudo apt-get install python-tk

## Usage


Run `python Learner.py` in terminal to see the the bot in action. It'll find the optimal strategy pretty fast

## Changes Made so far:

* modified the the game world so that it is now becomes bigger 
* more obstacles added
* bot position start randomly now.

## Demo

![Bot Demo](http://i.imgur.com/Ms6tcYr.png)







