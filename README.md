# Keypoints-Detection
The code uses data from the Kaggle Competition called 'Facial Keypoints Detection': https://www.kaggle.com/c/facial-keypoints-detection/data. The goal is to train a network to predict the location of 15 facial keypoints in each image.

The model created using Keras is trained on the training images. OpenCV Cascade Classifier is used to detect faces in the images. Following this step, the face is extracted from the image and the model predicts the keypoints only from the face. The keypoints are then mapped to the original image, giving the final results.
