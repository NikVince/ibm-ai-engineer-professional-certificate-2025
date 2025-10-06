# Course 2, Module 3: Summary and Highlights

## Overview
This module introduces the most popular deep learning libraries (TensorFlow, PyTorch, and Keras), focusing on Keras as a high-level API for building neural networks with ease and efficiency.

## Deep Learning Libraries
- **TensorFlow**: Used in production deep learning models with a very large community of users.
- **PyTorch**: Based on Torch framework in Lua, supports GPU-accelerated machine learning algorithms, preferred in academic research settings.
- **Keras**: High-level API for building deep learning models, known for ease of use and syntactic simplicity.

## Library Characteristics
- TensorFlow and PyTorch have steep learning curves and are not easy to use for beginners.
- Keras facilitates fast development due to its ease of use and syntactic simplicity.
- Keras can build complex deep learning networks with only a few lines of code.
- Keras typically runs on top of low-level libraries like TensorFlow.

## Data Preparation for Keras
- Before using Keras, data must be prepared and organized in the correct format.
- Datasets can be divided into predictors (features) and target (labels).
- For classification problems, target columns need to be transformed into arrays with binary values.
- Use the `to_categorical` function from Keras utilities package for binary transformation.

## Keras Workflow
- Build and train neural networks with only a few lines of code.
- Keras code can be used to build classification models efficiently.
- The library abstracts away complex low-level operations while maintaining flexibility.

## Takeaways
- Choose TensorFlow for production environments with large communities.
- Use PyTorch for academic research and GPU-accelerated algorithms.
- Leverage Keras for rapid prototyping and development due to its simplicity.
- Proper data preparation and formatting is essential before model building.
- Keras provides an accessible entry point into deep learning while maintaining power and flexibility.
