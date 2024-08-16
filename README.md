# Handwritten Digits Classifier
Classify handwritten digits with deep learning and neural network.
Building a neural network with hidden layers using TensorFlow to help with the classificaiton


DATASET: https://www.tensorflow.org/api_docs/python/tf/keras/datasets/mnist/load_data
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html

NOTE:
  - Each image in the dataset is 28 by 28 pixel
  - Takes in a Tuple of NumPy arrays [E.g. (x_train, y_train), (x_test, y_test) ]
  - Pixel values range from 0 to 255
  - NumPy array of digit labels (integers in range 0-9)
  
USEFUL DOCUMENTATION LINKS:
  - https://www.tensorflow.org/api_docs/python/tf/keras/Sequential
  - https://keras.io/api/losses/probabilistic_losses/#sparse_categorical_crossentropy-function
  - https://keras.io/api/layers/core_layers/dense
  - https://seaborn.pydata.org/generated/seaborn.heatmap.html
