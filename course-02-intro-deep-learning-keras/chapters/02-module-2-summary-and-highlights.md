# Course 2, Module 2: Summary and Highlights

## Overview
This module covers the fundamentals of deep learning training, including gradient descent optimization, the training loop process, the vanishing gradient problem, and various activation functions used in neural networks.

## Gradient Descent and Training
- Gradient descent is an iterative optimization algorithm for finding the minimum of a function.
- Learning rate balance: large rates can miss the minimum point, while small rates result in extremely slow convergence.
- Neural networks train by initializing weights and biases to random values, then repeating a four-step process:
  1. Calculate network output using forward propagation
  2. Calculate error between ground truth and predicted output
  3. Update weights and biases through backpropagation
  4. Repeat until epochs are reached or error falls below threshold

## The Vanishing Gradient Problem
- Caused by sigmoid activation functions preventing neural networks from training effectively.
- In simple networks, gradients become very small, especially for earlier layers.
- During backpropagation, multiplying factors less than one causes gradients to shrink exponentially.
- Earlier layers learn much slower than later layers, compromising training speed and accuracy.
- Sigmoid and similar functions are avoided due to this problem.

## Activation Functions
- Activation functions play a major role in neural network training.
- Seven main activation functions are available for building neural networks:
  - **Sigmoid**: Most widely used in hidden layers, but prone to vanishing gradient problems.
  - **Hyperbolic Tangent**: Scaled version of sigmoid, symmetric over the origin.
  - **ReLU**: Most widely used today, main advantage is not activating all neurons simultaneously.
  - **Softmax**: Ideally used in output layers for classification, provides probabilities for each class.

## Training Process
- Forward propagation calculates network output from input data.
- Error calculation compares predicted output with ground truth.
- Backpropagation updates weights and biases based on calculated errors.
- Process repeats until convergence criteria are met.

## Takeaways
- Choose appropriate learning rates to balance convergence speed and accuracy.
- Avoid sigmoid activation functions in deep networks due to vanishing gradient problems.
- Use ReLU for hidden layers and Softmax for classification output layers.
- Understand the training loop: forward propagation → error calculation → backpropagation → weight updates.
- Earlier layers in deep networks require special attention due to gradient flow issues.
