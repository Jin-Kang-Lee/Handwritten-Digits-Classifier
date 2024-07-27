# Handwritten_Digits_Classifier
Classify handwritten digits with deep learning and neural network.
Building a neural network with hidden layers using TensorFlow to help with the classificaiton


DATASET: https://www.tensorflow.org/api_docs/python/tf/keras/datasets/mnist/load_data

NOTE:
  - Each image in the dataset is 28 by 28 pixel
  - Takes in a Tuple of NumPy arrays [E.g. (x_train, y_train), (x_test, y_test) ]
  - Pixel values range from 0 to 255
  - NumPy array of digit labels (integers in range 0-9)
  
USEFUL DOCUMENTATION LINKS:
  - https://www.tensorflow.org/api_docs/python/tf/keras/Sequential
  - https://www.tensorflow.org/api_docs/python/tf/keras/losses/sparse_categorical_crossentropy
