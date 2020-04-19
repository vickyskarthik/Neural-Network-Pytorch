# Neural-Network-Pytorch
Repo to serve as tutorial for Neural Network Implementation using PyTorch

The various layers that make up any neural network are documented, [here.](https://pytorch.org/docs/stable/nn.html)

The conv_layer_visualization notebook can be used to understand the CNN Layer and its working. [source](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)

Please also checkout the [linked, exercise repo](https://github.com/udacity/CVND_Exercises/tree/master/1_5_CNN_Layers) for multiple solutions to the following training challenge!

##Training the Network
Typically, we train any network for a number of epochs or cycles through the training dataset

Here are the steps that a training function performs as it iterates over the training dataset:

1. Prepares all input images and label data for training
2. Passes the input through the network (forward pass)
3. Computes the loss (how far is the predicted classes are from the correct labels)
4. Propagates gradients back into the network’s parameters (backward pass)
5. Updates the weights (parameter update)

It repeats this process until the average loss has sufficiently decreased.
