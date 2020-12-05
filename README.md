# mnist_classification_problem

Neural networks is used to solve the classification problem using the mnist dataset. This dataset is formed of handwritten digits from 0-9. Keras is used to develop a neural network capable of predicting the handwritten digit.

The training and testing data are imported and the labels are one hot encoded. The training data possesses 60,000 images, but it is separated into validation and training data. The first image is plotted to verify everything is correct (see below).

![alt text](https://github.com/Johanfanas/mnist_classification_problem/tree/main/images/image.png)

A generator is used to feed the data in small groups. The model used is built using Keras built in functions and the model is trained.

![alt text](https://github.com/Johanfanas/mnist_classification_problem/tree/main/images/train.png)

After the model is trained, it is used to predict the handwritten digit with images from the testing data and verified they are correct. The accuracy of the model is evaluated using the testing data. We achieved a testing accuracy of approximately 75%.

![alt text](https://github.com/Johanfanas/mnist_classification_problem/tree/main/images/det.png)
