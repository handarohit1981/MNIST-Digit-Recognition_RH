# MNIST-Digit-Recognition_RH

In this notebook, we will train models to recognize digits from a dataset of hand-written digits called MNIST ("Modified National Institute of Standards and Technology") which has been used for benchmarking image classifiers. One potential business application of algorithmic identification of handwritten writing is the automatic digitization of handwritten documents. A model which can recognize human handwriting could be used to create a program that takes handwritten documents as input and returns a digitized document such as a PDF as output. 

There are many applications for this technology, such as converting student handwriting on exams to a digital format so that answers can be more easily read and graded by the proctor. 

* MNIST is known as a "hello world" dataset because it's very basic. 
* Each image is 28 by 28 pixels, represented in the data by 784 columns (one for each pixel) holding a value of 0 to 255 to represent darkness of the pixel, with higher values being darker.
* The dataset has 60,000 data points for the training set and 10,000 for the testing set. We will execute three models (SVM, and CNN) on this dataset and see which one performs the "best." 
* To determine this, we will measure the accuracy of the model, or the number of digits it correctly identified over the total number of digits in the dataset.



### SVM:
Support vector machines (SVMs) are particular linear classifiers which are based on the margin maximization principle. They perform structural risk minimization, which improves the complexity of the classifier with the aim of achieving excellent generalization performance. The SVM accomplishes the classification task by constructing, in a higher dimensional space, the hyperplane that optimally separates the data into two categories.

### CNN:
Convolutional Neural Networks (CNN) are feed forward artificial neural networks. They are highly acclaimed for their performance in computer vision tasks. CNN was based on the visual cortex found in animals. CNN is made up of an input layer, hidden layers, and an output layer. The hidden layers include layers that perform convolutions. A convolution kernal slides along the input layer which creates a feature map. This feature map is then passed into the next layer. There are also pooling layers to reduce the dimensions of the data along the network.


### Sources & References


* https://www.askpython.com/python/examples/load-and-plot-mnist-dataset-in-python

* https://link.springer.com/referenceworkentry/10.1007%2F978-0-387-73003-5_299

* https://analyticsindiamag.com/convolutional-neural-network-image-classification-overview/

* https://en.wikipedia.org/wiki/Convolutional_neural_network

* https://androidkt.com/get-the-roc-curve-and-auc-for-keras-model/
