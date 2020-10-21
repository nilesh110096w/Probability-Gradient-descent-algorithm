# Probability-Gradient-descent-algorithm
A new algorithm to modify Drop out probability of neural nets dynamically instead of using it as a hyper parameter. Here we start with a high drop out rate for more generalization and as loss function decreases we try to reduce generalzation by reducing drop out rate based on difference in previous and current loss function. Therefore in initial iteration, network is more focused on generalization and generalization is removed at the end of algorithm and hence this algorithm is expected to perform generalization and reduction in training error simuntaneously.

#Data set used
I have used MNIST fashion dataset.

#Library used
Tensorflow Keras is the main library for model training
