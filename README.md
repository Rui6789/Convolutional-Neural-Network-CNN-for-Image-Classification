# CNN for Image Classification
**1.Installations**
The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- tensorflow (including Keras)
- os
- pathlib

### 2. Project Motivation
The goal of this project is to build a convolutional neural network (CNN) model using TensorFlow and Keras to classify images as either a dog or a cat. The model will be trained on a dataset of 4000 dog images and 4000 cat images, and then evaluated on a test set of 1000 dog images and 1000 cat images. Finally, the trained model will be used to make predictions on a set of single images in the "single_prediction" folder.

The key steps in the project are:

- Importing the Libraries: The necessary libraries, including TensorFlow, Keras, and supporting libraries, are imported at the beginning of the script.
- Preprocessing the Training and Test Sets: The training and test datasets are preprocessed using the ImageDataGenerator from Keras. The images are resized to a common size (150x150 pixels) and normalized.
- Building the CNN Model: The CNN model is built using Keras' Sequential API. It consists of convolutional layers, max-pooling layers, dropout layers, and a final dense layer for binary classification (dog or cat).
- Training the CNN Model: The model is trained on the preprocessed training set for 10 epochs, with a batch size of 32.
- Evaluating the CNN Model: The trained model is evaluated on the preprocessed test set, and the accuracy score is reported.
- Making Predictions on Single Images: Finally, the trained model is used to make predictions on the single images in the "single_prediction" folder. The predicted class (dog or cat) is printed for each image.

### 3. File Descriptions
The dataset can be downloaded [here](https://drive.google.com/file/d/1Rq98J1gHTnfOaNCvX41tThi4-Pe80loA/view?usp=sharing)

The project consists of the following files:

- train_set: This directory contains the training dataset, with 4000 dog images and 4000 cat images.
- test_set: This directory contains the test dataset, with 1000 dog images and 1000 cat images.
- single_prediction: This directory contains a set of single images to be classified by the trained model.
- cnn_dog_cat.py: The report of my project is called 'CNN for Image Classification.ipynb.'

### 4. Results
The final CNN model achieves an accuracy of approximately 99% on the test set, demonstrating its effectiveness in classifying dog and cat images. The model can then be used to make predictions on new, unseen images. The main findings of the code can be found at the post on Medium available [here](https://medium.com/@mma1_65597/convolutional-neural-network-for-dog-vs-cat-image-classification-79a2af9717a3)

### 5. Licensing, Authors, Acknowledgements, etc.

The Author of this report is Mingrui Ma, with the student number 0447039. Data for coding project was provided by Prof.Abbasi Amiri, F. Thanks a lot to his instructions.
