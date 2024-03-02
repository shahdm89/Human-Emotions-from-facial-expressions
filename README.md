# Human-Emotions-from-facial-expressions

## Image Classification using CNN
This repository contains code for building a deep learning model to classify images into happy and sad categories using Convolutional Neural Networks (CNN) implemented in TensorFlow and Keras.

### Overview
#### The code performs the following steps:

Importing Libraries: Necessary libraries including TensorFlow, OpenCV, Matplotlib, and scikit-learn are imported.

Data Cleaning: Images are cleaned to remove unsupported file formats or corrupted data.

Loading Data: Image dataset is loaded and visualized using TensorFlow's image_dataset_from_directory function.

Data Augmentation: Data augmentation is performed to increase the diversity of the dataset and enhance model generalization.

Splitting Data: The dataset is split into training, validation, and test sets for model evaluation.

Building Model: A CNN model is constructed using Keras Sequential API with convolutional and dense layers.

Training: The model is trained on the training data with validation on a separate validation set.

Plotting Performance: Training metrics such as loss and accuracy are plotted for performance evaluation.

Evaluation: The model is evaluated on the test set using metrics like precision, recall, and accuracy.

Testing: A sample image is tested to demonstrate the model's prediction capability.

Saving Model: The trained model is saved for future use.

For detailed implementation and usage instructions, please refer to the code comments and documentation within the respective files.
