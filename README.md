# MNIST-Digit-Classification

In this notebook I have trained 3 models. First one is a directly connected neural network, second is a fully connected feed forward neural network and third one is the a convolutional neural network. All the 3 models have been written in keras library. The accuracy and loss of all the 3 models for 30 epochs is plotted for comparision.

# Accuracy

From "Model Accuracy.png" we can see that as the number of epochs increase, the train and validation accuracy increases rapidly initially, but then almost saturates for higher epochs. Also the accuracy is not exactly monotonic as expected in theories, but keeps on going up and down. 
When we compare the train and validation accuracies of fully connected network and CNN, we can see that even though CNN have lower train accuracy than directly connected network, it have better validation accuracy.

# Further Work

Anyone who wants to add some more models for comparision is welcome to do so.
