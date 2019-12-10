# Deep-learning-practical-work
Compilation of some practical work around deep learning thematic

___

## Learning section: pratical examples with Keras framework
From the book *Deep learning with Python* from François Chollet
* Classifying movie reviews - binary classification example
* Classifying newswires - multiclass classification example
* Predicting house prices - regression example
___

## 1. Multi-Layer Perceptron for classification, only using numpy
Full implementation of a two layers Multi-Layer Perceptron (MLP) with 1 hidden layer in Python, for a classification problem.
* Forward propagation
* Computation of the cost/loss
* Backward propagation
* Parameters udpate

## 2. Different implementations for MLP binary classification with pytorch
Three different implementations:
* **Model 1**: manually defining the parameters `W1,b1,W2,b2,W3,b3`, writing the forward equations, writting the loss equation, calling the `.backward()` and manually updating the weights using `W1.grad`.
* **Model 2**: using the `Sequential` class of pytorch
* **Model 3**: a custom `torch.nn.Module` class.

## 3. Music sequences generation
Training a RNN language model to generate cello suite sequences.
