# Skillhigh_handwritten_digit_detection
The handwritten digit detection is done by using a specific kind of artificial neural network called Convolutional Neural Network. It is a deep leaning algorithm used for evaluating the images or other grid information.
It is made using a convolutional layer to extract features , pooling layer and fully connected layers with Softmax activation function for multi-classification.
The model successfully recognize all 10 digits and attains an accuracy of 94%
Used 'adam' which is a self-adjusting optimizer
Loss is calculated using sparse categorical crossentropy loss function
The vanishing gradient descent is also taken care off by using 'relu' function. It is a condition in which due to multiple hidden layers between input and output layer, while backproporgation the learning rate becomes very low and the gradient become very small, providing less improvement to starting layers.
