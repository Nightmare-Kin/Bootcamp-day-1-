# Bootcamp-day-1- Basic Neural Networks and AI
Machine Learning Cycle: Data Collection, Pre-Processing, Data Cleaning, Feature Engineering, Model Training, Testing, Deployment, Maintenence 

Linear Regression: Statistical Technique that models a set of points by choosing a linear equations that best fits it

Logistic Regression: Statisitcal Model that estimates the probability of a binary outcome by applying a logisitc function

Neural Network: 3 main layers: Input layer, Hiden Layers, Output Layers
  Takes inputs and feeds them through the hidden layers by assigning weights ( from 0.0 - 1.0 ) on each input per hidden layer node. The hidden layer runs the weights through a function ( like a Sigmoid ) and adds the bias before transmitting its response to the next layer. The output layer takes all the responses, takes the best ones, and outputs it.

2 Main activation functions:
    - Sigmoid ( 1/(1-e^-x)
    - ReLU: ( if <x then 0, if >x, return x )

Gradient Descent Algorithm: Calculates slope of a random point of graphed errors and moves to find the global minimum error ( best output ).

2 types of Gradient Descent:
  - Batch Gradient Descent ( calculates using whole sample at once )
      - Slower ( Has to use the entire data collection at once, creating a slower runtime )
      - Gets an optimal solution by considering the entire dataset at once
      - Gets stuck on LOCAL minimum
  - Stochastic Gradient Descent:
      - Runs through one training sample at a time
      - Faster ( one sample at a time requries less storage and makes computing faster )
      - Good solution not optimal ( Can generalize due to going one sample at a time. )
      - Does NOT get stuck on local minimum 

Overfitting: When the model is trained on low effort data and conforms to only recognize that data
Underfitting: Model is given data above its capabilities and defaults to a overgeneralization of all data

CODE INCLUDED - Property of the code is not mine; Provided by "Harvard Ai Group"

Basic Neural Network: 1 input layer( 2 nodes ), 1 hidden layer( 4 nodes ), 1 output layer ( 1 node ) 
Uses pytorch Resources 
Performs analysis for XOR problem



  

  

 


