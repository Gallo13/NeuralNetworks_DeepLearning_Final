# NeuralNetworks_DeepLearning_Final
Forward and Backward Modes of Neural Network

Execute forward and backward modes of neural network by hand or by using Python (your choice) for 3 iterations (epochs). The model is shown in Fig. 1. This network comprises of a hidden layer with 3 ReLU units and a squared-error loss. (Note: Use tanh as activation function in the output unit and ReLU for hidden layer)

Notice that this function is non-differentiable around 0. Therefore, when computing your gradients, you will have to compute one gradient if the input is larger than 0, another if it is smaller than 0, and ignore when the input is 0 and thus non-differentiable.)

weights: [W11 W21 W31] = [0.60 0.70 0.00
         [W12 W22 W32] = [0.01 0.43 0.88]
         
         [W11]    [0.02]
         [W12] =  [0.03]
         [W13]    [0.09]
         
Data: [x1] = [0.75 0.80]
      [x2] - [0.20 0.05]
      [x3] = [-0.75 0.80]
      [x4] = [0.20 -0.05]

Their corresponding labels are y = [1, 1, −1, −1].

You may use the recursive patterns to update parameters of this network.
