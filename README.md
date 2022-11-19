# Train Neural Networks (NN) with Delta rule

This repository contains our teamwork ([Ilaha Manafova](https://www.linkedin.com/in/ilaha-manafova/) & I) projects in the context of *"Technical Neural Networks (TNN)"* course taught by Prof. Goerke at the University of Bonn.

We were supposed to train a:

1. [Perceptron with Delta rule](#perceptron-with-delta-rule)
2. [MLP with Delta rule]()

## Perceptron with Delta rule
We implemented a Perceptron with Delta rule in Python. 

<p align="center">
  <img src="figures/perceptron.png" width="25%">
  </br>
  Illustration of a Perceptron neuron
</p>

The Perceptron was trained with different data, mostly representing boolean operators e.g. `OR` and `AND`, for different times. We used Logistic function as an activation function and MSE as a loss function. The learning rate was set to 0.5 and the number of epochs was set to 500. The following figures show the learning curves for different data:

<p align="center">
  <img src="figures/perceptron_learning_curves.png" width="75%">
  </br>
  Learning curves for different data
</p>

