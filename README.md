# Mountain-Car_Reinforcment-learning-Project
A car is on a one-dimensional track, positioned between two “mountains”. 
The goal is to drive up the mountain on the right in as few steps as possible; however, the car’s engine is not strong enough to scale the mountain in a single pass. 
Therefore, the only way to succeed is to drive back and forth to build up momentum.

The car’s state, at any point in time, is given by a vector containing its horizontal position and velocity. 
The car commences each episode stationary, at the bottom of the valley between the hills (at position approximately -0.5), 
and the episode ends when either the car reaches the flag (position > 0.5) or after 200 moves.

At each move, the car has three actions available to it: push left, push right or do nothing, 
and a penalty of 1 unit is applied for each move taken (including doing nothing). 
This means that, unless it can figure out a way to ascend the mountain in less than 200 moves, it will always achieve a total “reward” of -200 units.

#Mountain Car Problem description: 
https://en.wikipedia.org/wiki/Mountain_car_problem

#The model used (QLearning): 
https://en.wikipedia.org/wiki/Q-learning

#Hint:
More info and observations are existed in the "Report.pdf" file.
