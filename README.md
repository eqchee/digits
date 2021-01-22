# Image Classification using Naive Bayes Classifier

A simple model is developed to classify the handwritten digits on images by applying Bayes' theorem.

For a given image of size 28 pixels by 28 pixels, there will be a total of 784 pixels used to illustrate the image. These 784 pixels would then contain a value to indicate if it is bright or dark. By applying Bayes' rule to the joint probability, the model would thus compute the probability of each class, ie c = 0, c = 1, ... , c = 9 given the pixel values and the digit is predicted based on the highest computed probability.

With this simple model, an accuracy of 83.75% was achieved.


# Image Classification using Convolutional Neural Network (CNN)

To classify handwritten digits on images, Deep Learning was utilised by creating a Convolutional Neural Network (CNN) using TensorFlow. The CNN model was structured using a series of different layers:

- Convolutional layer to isolate useful features from the images
- Pooling layer to facilitate dimensionality reduction and extraction of dominant features.
- Dropout layer for regularization to reduce overfitting
- Flatten layer to convert the feature maps into a single 1D vector

An accuracy of 98.8% was achieved when the predictions were submitted to Kaggle.
