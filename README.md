# Digit_Recogniser
My project is to identify digit(0-9) from a dataset of hand written digits.
The dataset I have used is mnist which contains 28x28 images of hand written digits and their labels.
I have used deep learning with TensorFlow to perform this task.
I have created a deep neural network that contains one input layer,two hidden layers and one output layer.
I have used a sequential model which is a feed forward model.
The hidden layers consist of 128 neurons or nodes,and the activation function used is relu(rectified linear).
The output layer consists of 10 nodes,one for each digit.Softmax activation function is used in this layer for probability distribution.
Finally,adam optimizer is used to compile the model.Categorical crossentropy loss metric is used since my neural network aims to minimize the loss and also because I'm performing a classification task.
