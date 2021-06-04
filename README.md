# Cat-Dog-Classifier :dog: :cat:

The purpose of this project is to train a model that can classify images of dogs and cats into two separate groups.

In the first to fourth parts, an attempt is made to train the model without the use of a convolutional neural networks, and in general, in each of the second to fourth parts, an attempt is made to select the best one for this problem by examining various hyperparameters.
<!-- This project was done as a team by me and @MKasaei00. -->

## What we do need? :bell:

```
Keras
Tensorflow
Scikit learn
Numpy
OpenCV
Matplotlib
```

If you can not use GPU, using Google Colaboratory you can use the gpu to train your model. :sunglasses:

## Create a Deep Neuaral Network without using CNN :weary:

### [Part 1](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/CatDogClassifier_Part_1.ipynb)
Designing the primary neural network

In this part, the initial neural network was designed and implemented. Drop-out and data aggravation have also been used to solve the problem of over-fitting of the model.

In addition, the performance of the model was evaluated by various criteria such as accuracy, Percision, Recall and F1-measure.

### [Part 2](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/CatDogClassifier_Part_2_batch.ipynb)
Neural Network performance is assessed by selecting and reviewing different learning rates and batch sizes.

### [Part 3](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/CatDogClassifier_Part_3.ipynb)
In this section, we examined the number of layers and hidden layer neurons in different states.

### [Part 4](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/CatDogClassifier_Part_4.ipynb)
In this section, we reviewed 100 examples of images that the model could not correctly identify and proposed and implemented several solutions to solve this problem.

**Result: In this part, we finally reached 67% accuracy!** :smiley:

## Create a Deep Neural Network with the help of CNN and transfer learning :innocent:

### [Part 5](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/CatDogClassifier_Part_5.ipynb)

We used inception v3 to build a deep neural network in this section.

In the following, we see the schematic of this network:


<img src="https://cloud.google.com/tpu/docs/images/inceptionv3onc--oview.png">

By using this deep neural network and adding several layers of convolutional neural network to it, we were able to achieve **96%** accuracy. :heart_eyes: :heart_eyes: 

## Support

**Contact me @:**

e-mail:

* farzanehkoohestani2000@gmail.com

Telegram id:

* [@farzaneh_koohestani](https://t.me/farzaneh_koohestani)

## License
[MIT](https://github.com/farkoo/Cat-Dog-Classifier/blob/master/LICENSE)
&#0169; 
[Farzaneh Koohestani](https://github.com/farkoo)




