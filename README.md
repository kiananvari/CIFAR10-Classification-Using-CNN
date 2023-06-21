
# CIFAR10 Images Classification
In this project, I implemented a Convolutional Neural Network (CNN) for classifying images in the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The objective of the project was to find the best CNN architecture to achieve high accuracy in classification.



## Dataset

The CIFAR-10 dataset was used for training and testing the CNN. The dataset was downloaded directly from the official website (http://www.cs.toronto.edu/~kriz/cifar.html). The dataset consists of 50,000 training images and 10,000 testing images.


## Preprocessing
Before feeding the images into the CNN, some preprocessing steps were applied. The images were first normalized to have zero mean and unit variance. Data augmentation techniques such as random horizontal flipping and random cropping were also applied to increase the size of the training set and improve the performance of the CNN.


## Documentation

You can see the description of the implementation method in the following file:
[Click Me](https://github.com/kiananvari/CIFAR10-Classification-Using-CNN/blob/main/Documentation.pdf)


## Results

The performance of each CNN architecture was evaluated based on the accuracy achieved on the test set. The best performing architecture was found to be the Inception model, which achieved an accuracy of 94% on the test set. The other architectures also achieved high accuracy, with the worst performing architecture achieving an accuracy of 83%.

![App Screenshot](https://github.com/kiananvari/CIFAR10-Classification-Using-CNN/blob/main/Results/plot.png)

![App Screenshot](https://github.com/kiananvari/CIFAR10-Classification-Using-CNN/blob/main/Results/train.png)

![App Screenshot](https://github.com/kiananvari/CIFAR10-Classification-Using-CNN/blob/main/Results/test.png)

