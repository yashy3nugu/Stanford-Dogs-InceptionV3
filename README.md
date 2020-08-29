# Stanford-Dogs-InceptionV3

# Stanford Dogs dataset Classifier
by Yashaswi Yenugu

# The Dataset
The Stanford Dogs dataset has images of 120 dog breeds from around the world.

The contents of the dataset are:
- ***Number of Categories*** = 120
- ***Total Number of images*** = 20,580

The number of images per dog breed is low to train a neural network from scratch.
Hence it would be beneficial to use transfer learning. 
The dataset is imported from Kaggle.
The data can be found at https://www.kaggle.com/jessicali9530/stanford-dogs-dataset


# Inception V3
InceptionV3 is a convolutional neural network for assisting in image analysis and object detection, and got its start as a module for Googlenet. It is the third edition of Google's Inception Convolutional Neural Network, originally introduced during the ImageNet Recognition Challenge.
The model network uses the weights of the inception network trained on the 'imagenet' database and frozen.


# Challenges The network might face
The dataset contains dog breeds which are visually similar to each other.
This might cause challenges for the network.

As you can see Swiss mountain dogs and Bernese Mountain dogs are very similar

![Swiss mountain dog and Bernese mountain dog](swiss.jpg)


