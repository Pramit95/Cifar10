This project showcases a Convolutional Neural Network based architecture to classify images from the Cifar-10 dataset.
My model achieves an accuracy of 90.2 percent and can be further improved with more training.
I trained the model on Google Cloud Platform's Vertex AI with 1 GPU.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes. There are 50000 training images and 10000 test 
images." -( https://www.cs.toronto.edu/~kriz/cifar.html ).

I have designed an architecture adapted from the VGG16 model Very Deep Convolutional Networks for Large-Scale 
Image Recognition (ICLR 2015)[https://arxiv.org/abs/1409.1556], and changed the last 2 layers and added regurization techniques inspired from 
Very deep convolutional neural network based image classification using small training sample size [https://ieeexplore.ieee.org/document/7486599].
