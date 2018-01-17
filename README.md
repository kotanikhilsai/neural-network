# neural-network
this is a neural network containing 3 layers
the 1st later contains 4 perceptrons and tanh(x) is the activation function
the 2nd later contains 3 perceptrons and tanh(x) is the activation function
the last layer or the ouput layer contains 1 perceptron which uses sigmoid(x) as activation function


note: the above model is trained only on 2 types of iris flowers of the dataset because the sigmoid function is a binary classifier
and hence cannot classify among 3 types of flowers .
inorder to classify among more than three we can select softmax function as the activation function for output layer

the accuracy is about 75% and will change with changes in no of iterations and learning rate
