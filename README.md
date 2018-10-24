# Cats-vs-Dogs-Dataset

The Original Cats vs Dogs Dataset consists of 25,000 training images. I've selected only 2,000 images for training set, 1,000 images for validation set and further 1,000 images for test set. Given a random image, we have to identify it as a cat or a dog. This shortened dataset in stored on Google Drive and each file contains code on how to access the dataset on Drive.

I've implemented 3 different neural networks. The first one (Cats_Dogs_7520.ipynb) consists of bunch of Convolution and Pooling layers, all trained from scratch, it also makes use of ImageDataGenerator for Data Augmentation. This gives 75.20% accuracy on 30 epochs. The second implementation (Cats_Dogs_8890.ipynb) makes the use of Fast Feature extraction without Data Augmentation. This gives 88.90% accuracy after training for 30 epochs. This method is used when we need to train the model fast. The third model (Cats_Dogs_9319.ipynb) uses a pre-trained VGG16 model, initially with a self-trained classifier, and again with fine tuning of the fifth convolutional block and the self-trained classifier. This gives 93.19% accuracy on 100 epochs.

Thus, the various techniques of applying Convolution Neural Networks in Image Classification are shown, and the results clearly indicate which methods are superior in terms of accuracy.

All implementations are made using Keras. This example was inspired by the book Deep Learning with Python written by Keras author Francois Chollet.

Comments and Suggestions are welcome :)

Author: Swarup Padhy(3rd October, 2018)
