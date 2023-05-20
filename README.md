# A1-Exercise1
An exercise on Neural Networks

As required for this exercise, the number of hidden layers, neutrons and activation function is changed. The number of hidden layer is changed to 4 with 128, 64, 64 and 32 neutrons. And the activation function is changed to tanh.

The model produced a val-accuracy of 0.987 which is close to 1. This is an indication that my model, with the changed hidden layer, neutrons and activation function, is neither underfitted nor overfitting for the dataset.

I also plotted the residual training and testing but there is a little change in this plot as compared to the former one. The graphs of the training and testing in model loss and accuracy approaching to 0 and 1 respectively, indicates that my neural network model can be considered fitting for the dataset (oversitting or underfitting).

However, on closer observation, the exponetial testing line (orange) in the model loss is observed to have ascended to 0.1 after reaching its minimum point at 10 epoch. This accounts for slight model loss. This also applies to the exponetial testing line (orange) in the accuracy model observed to descend to 0.985 after it reached its maximum point at roughly 7 epoch. This accounted for slight error in the model accuracy. The confusion matrix is also plotted to evaluate the performance of the model. From the matrix, it is observed that there is no type I or type II error.
