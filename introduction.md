# What is Deep Learning?

Deep Learning is a subset of Machine Learning that uses multi-layered neural networks.

The recent success of deep learning is due to the following three features:

* Infinitely flexible function (universal approximator)
* All purpose parameter fitting (optimization)
* Speed and Scalablility

## Overfitting and Generalization

Overfitting: If you have a flexible enough function (with enough tunable parameters) it can just memorize your training data.

Generalization: If your function performs just as well on data it has never seen as it does on training data, it is said to "generalize" well.

## The General Recipe (for image classification)

1. Collect and hand-label images
2. Split dataset into training and validation sets
3. Choose an architecture (model) and hyperparameters
4. Train model (repeat these steps):
  1. Run a mini-batch of training images through the model
  2. Calculate loss
  3. Adjust model parameters
  4. Run validation data through the model (don't adjust parameters though!)
5. Evaluate performance (unhappy? goto 3)

## Neural Networks

Show clip from: [3blue 1brown](https://www.youtube.com/watch?v=aircAruvnKk) ~4 mins
