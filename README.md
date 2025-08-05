# Practice-Self-Driving-Car
This is a practice of a self driving car where we can draw roads to train the car to stay on the road. This is a sample project which uses DQN method to build the car brain
car.kv file contains the design of car which will run in a separate window to train how to stay on the track. .pth file contains the weights of the car's learning policy so that if we start retraining, then the card shouldn't start train from the scratch.
map.py contains all the necessary classes to draw the map and laws.
ai.py contains the main reward and NN design for the whole training
