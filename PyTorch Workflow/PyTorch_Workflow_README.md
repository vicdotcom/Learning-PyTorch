## PyTorch Workflow
Here we cover a standard machine learning workflow by constructing a simple linear regression model in PyTorch. This workflow entails:
1. Loading and preparing the data
2. Model building and training/fitting where we optimize the model's parameters to decrease the error between the predicted output and actual values.
3. Making predictions and evaluating the model's output against actual data.
4. Saving and loading a pre-trained model.

### Topics covered
As part of the ML workflow we cover:
- Data splitting (Training, Validation, Testing sets)
- Building a simple Linear Regression model via PyTorch which consists of:
-     - Parameter initializations
      - Defining a loss function and optimizer for the model
- Constructing model training loops that run through the data
- Model evaluation
- How to tell if a model is well-fit/overfitted/undefitted
- Saving and loading the model for future use

### Prerequisites
Would be benefitial to have some knowledge on:
- Object oriented programming (OOP) in Python. Most models in PyTorch are constrcuted while implementing OOP concepts. 
- Backpropagation- This is how the model updates its parameter weights
- Loss function- The error between the model's predictions and te actual value/label
- Gradient descent- This is how the model minimizes loss. There is also Stochastic Gradient Decscent which you should also have an idea about.
    
