# CIFAR10
This is the Cifar 10 Dataset, a very famous dataset that contains images for 10 different categories:

airplane
automobile
bird
cat
deer
dog
frog
horse
ship
truck

Here's what we have to do:

load the cifar10 dataset using keras.datasets.cifar10.load_data()
display a few images, see how hard/easy it is for you to recognize an object with such low resolution
check the shape of X_train, does it need reshape?
check the scale of X_train, does it need rescaling?
check the shape of y_train, does it need reshape?
build a model with the following architecture, and choose the parameters and activation functions for each of the layers:
conv2d
conv2d
maxpool
conv2d
conv2d
maxpool
flatten
dense
output
compile the model and check the number of parameters
