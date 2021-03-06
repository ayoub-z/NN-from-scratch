# Machine-learning (neural networks)
#### Repository for all machine learning assignments.
In this repo we create a neural network from scratch (P 1-4).
And use tensorflow to classify the 10 different classes of images in the CIFAR-10 dataset (P5)


## P1_perceptron:
Contains the following:
  - Perceptron (Perceptron unit. Basically a neuron that takes input and has weights)
  - PerceptronLayer (A single layer (in the network) that contains and handles multiple Perceptrons)
  - PerceptronNetwork (The neural network that holds each and every layer)
  - Main (Used to initialize Perceptrons/layers/network in order to test the code)
-------------

## P2_learning_rule: 
Contains the following:
  - Perceptron that is able to adjust it's own weights and bias with the learning rule
  - Jupyter notebook to test and validate the trained networks.
-------------

## P3_neuron:
Contains the following:
  - Exactly the same as Practicum 1, except that it uses the Sigmoid activation function. <br/>
  - Weights and biases for the XOR and HALF ADDER are adjusted in the `main.py` in order to reach 0/1 outputs.
-------------

## P4_backpropagation:
Contains the following:
  - Neuron with sigmoid activation function. 
  - Neuron layer. Contains the hidden and/or the output layer(s) with all their neurons.
  - Neuron network. Network is activated with feed_forward and is trained/updated with backpropagation.
  - Jupyter notebook to train and test NN on certain datasets.

## P5_tensorflow_CIFAR:
  - Train a neural network to classifiy images in the CIFAR dataset
