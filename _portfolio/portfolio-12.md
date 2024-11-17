---
title: "DQN Reinforcement Learning AI"
excerpt: "My first real attempt at slightly more complex reinforcement learning using python.<br/><img src='https://imgur.com/HFt7Iij.jpg'>"
collection: portfolio
---

In this project, I wanted to learn about deep reinforcement learning algorithms and teach games how to play themselves. For this project, I managed to train AI how to play CartPole and MountainCar, I have uploaded the project to GitHub along with the trained AI module and the output logs so they can be tested. If you clone the branch and open terminal you can test the AI by typing: "py agent.py cartpole1"

The project is built in python, using the OpenAI Gym framework to pull a game and display it on screen. This is an advancement on my original RL project, while the project is running in the background I get it to plot graphs every minute to see the progress of the reward gained and the epsilon decrease in order to make sure it is progressing as expected even though I am unable to see the training (although I can set the training to render if I wish).

I do want to push this project a bit futher, possibly make my own game with my own reward systems to be able to create an AI to complete it. So start of small, make snake or connect-4 maybe and create an AI that can either complete snake or a duelling AI that can play agaist itself in connect-4.

The source code is available here for review [here.](https://github.com/JackDKillelea/dqn-rl)