# Cat-Dog-Classifier

The purpose of this project is to train a model that can clasify images of dogs and cats into two separate groups.

In the first to fourth parts, an attempt is made to train the model without the use of a convolutional neural networks, and in general, in each of the second to fourth parts, an attempt is made to select the best one for this problem by examining various hyperparameters.

## What we do need?

```
Keras
Tensorflow
Scikit learn
Numpy
OpenCV
Matplotlib
```

If you can not use GPU, using Google Colaboratory you can use the gpu to train your model.

## Create a Deep Neuaral Network without using CNN

### Part 1
Designing the primary neural network

In this part, the initial neural network was designed and implemented. Drop-out and data aggravation have also been used to solve the problem of over-fitting of the model.

In addition, the performance of the model was evaluated by various criteria such as accuracy, Percision, Recall and F1-measure.

### Part 2
Neural Network performance is assessed by selecting and reviewing different learning rates and batch sizes.

### Part 3
In this section, we examined the number of layers and hidden layer neurons in different states.

### Part 4
In this section, we reviewed 100 examples of images that the model could not correctly identify and proposed and implemented several solutions to solve this problem.

**Result: In this part, we finally reached 67% accuracy!**

## Create a Deep Neural Network with the help of CNN and transfer learning

### Part 5

We used inception v3 to build a deep neural network in this section.

In the following, we see the schematic of this network:


<img src="https://cloud.google.com/tpu/docs/images/inceptionv3onc--oview.png">

By using this deep neural network and adding several layers of convolutional neural network to it, we were able to achieve 96% accuracy.



