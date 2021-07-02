# Project3_Collaboration_and_Competition
The third project in the udacity deep-reinforcement-learning nanodegree

Note: This repository is created for Linux ubuntu 21.04. It's only guaranteed to work on this version. Nonetheless it should work on other Linux versions as well.

## The Task
This GitHub repository is designed to solve the Unity ML-Agents Tennis Environment.

## The environment
![Unity ML-Agents Tennis Environment](Udacity_Collab_and_Comp.gif)

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). It's important to mention that after each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores. This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## Getting started

Before running the code in the jupyter-notebook make sure to install the necessary libraries. If you'd like to install them on your own machine please follow the instructions below. These instructions imply that your machine already satisfy conditions to run all, not explicitly for this project necessary, requirements like for example jupyter notebooks or python3-code.

To use this repositotry on your own machine please set up a python-environment. In order to do so please follow the instructions in this repository: https://github.com/udacity/deep-reinforcement-learning#dependencies.

## Use the Code

In order to use the code in this repository make sure your machine satisfy  all requirements in the "Getting started"- paragraph above. Now you are free to clone this repository and use it on your own computer (No GPU-support needed). After cloning, you have to open the terminal-window and navigate to the folder representing the repository (The repository should be placed in your python-environment). Please open a jupyter notebook using the *jupyter notebook* command. The Notebook will open in your browser. Thereafter you have to open the *Collaboration_and_Competition_Training.ipynd*-file and restart the kernel by clicking on the "restart"-button. A dialogue will open, please click on the "restart and run all cells"-button. Finally the agents train. If you prefer watching an already trained agent, please open the *Collaboration_and_Competition_Trained_Agents_Test.ipynd*-file.

**For additional information please read the "Report.md"-file**
