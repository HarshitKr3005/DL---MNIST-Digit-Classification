# MNIST Text Classification
This repository contains code for text classification using the MNIST dataset. The MNIST dataset is a collection of handwritten digits widely used for training various image processing systems. In this project, we treat each digit as a separate class and perform text classification using machine learning techniques.

## Dataset
The MNIST dataset consists of 60,000 training images and 10,000 testing images. Each image is a 28x28 pixel grayscale image of a handwritten digit from 0 to 9. The dataset is split into training and testing sets to evaluate the performance of the classification model.

## Model Architecture
We employ a simple convolutional neural network (CNN) architecture for text classification. The CNN consists of multiple convolutional layers followed by max-pooling layers to extract relevant features from the input images. Finally, the features are flattened and fed into a fully connected neural network for classification.

## Results
After training the model, you can view the performance metrics such as accuracy, precision, recall, and F1-score on the test set. Additionally, you can visualize the classification results and explore the misclassified digits for further analysis.
