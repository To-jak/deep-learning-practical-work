# Deep Learning practical work
Compilation of some practical work around deep learning thematic.

___

## Learning section: pratical examples with Keras framework
From the book *Deep learning with Python* from François Chollet
* [Classifying movie reviews](./learning_with_keras/Classifying_movie_reviews.ipynb) - binary classification example
* [Classifying newswires](./learning_with_keras/Classifying_newswires.ipynb) - multiclass classification example
* [Predicting house prices](./learning_with_keras/Predicting_house_prices.ipynb) - regression example
* [Quick convnet model for MNIST dataset classification](./learning_with_keras/Keras_convnet_quick_model.ipynb)
* [Cats and dogs](./learning_with_keras/training_CNN_from_scratch_on_a_small_dataset.ipynb) - from scratch CNN classification example on a small dataset
___

## Multilayer perceptron
MLP implementations. *Work done in Geoffroy Peeters's deep learning course at Telecom Paris.*
### 1. [Multi-Layer Perceptron for classification only using numpy](./multilayer_perceptron/MLP_python.ipynb)  
Full implementation of a two layers Multi-Layer Perceptron (MLP) with 1 hidden layer in Python, for a classification problem.
* Forward propagation
* Computation of the cost/loss
* Backward propagation
* Parameters udpate

### 2. [Different implementations for MLP binary classification with pytorch](./multilayer_perceptron/MLP_pytorch.ipynb)
Three different implementations:
* **Model 1**: manually defining the parameters `W1,b1,W2,b2,W3,b3`, writing the forward equations, writting the loss equation, calling the `.backward()` and manually updating the weights using `W1.grad`.
* **Model 2**: using the `Sequential` class of pytorch
* **Model 3**: a custom `torch.nn.Module` class.

## Recurrent neural network
### 1. [Music sequences generation](./recurrent_neural_network/Generating_music_sequences.ipynb)
Training a RNN language model with LSTM layers to generate cello suite sequences. *Work done in Geoffroy Peeters's deep learning course at Telecom Paris.*
![](images/music_generation.PNG)

## Convolutional neural network
*Work inspired after Alasdair Newson's deep learning course at Telecom Paris.*
### 1. [Deep dream algorithm implementation](./convolutional_neural_network/deep_dream_algorithm_example.ipynb)
Implementation of the weird "deep dream" algorithm, a fun way to vizualize what convolutional networks are learning.
![](images/deep_dream_example.PNG)

### 2. [Adversarial example for CNN](./convolutional_neural_network/adversarial_example_for_cnn.ipynb)
Implementation of a quick adversarial case for a convolutional network, to fool it and force misclassification using gradient maximisation.
![](images/adversarial_example.PNG)
  
## Introduction to GPU programming
*Work done during Elisabeth Brunet and Tamy Boubekeur course at Telecom Paris*
### 1. [Matrix Multiplication with CUDA](./gpu_programming/MatMult.ipynb) 
### 2. [Parallel Reduction with CUDA](./gpu_programming/reduction.ipynb) 
Implementation of different reduction techniques from [this presentation](https://developer.download.nvidia.com/assets/cuda/files/reduction.pdf) of H. Harris.
### 3. [Classification and Gradient Descent with cuBLAS](./gpu_programming/cublas_classification_gradient_descent.ipynb) 
