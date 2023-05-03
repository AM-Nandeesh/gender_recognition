# gender_recognition

The code trains a deep learning model for gender detection from facial images using the Keras library. It uses a convolutional neural network architecture, and the Adam optimizer with binary cross-entropy loss function to train the model. The training data is augmented with various transformations using ImageDataGenerator. The trained model is saved and used for live gender detection on webcam video streams. The face detection and cropping is done using the cvlib library. Finally, the model is used to predict the gender of the cropped face images, and the result is displayed on the frame.


the images for training data sets are taken from : https://drive.google.com/file/d/110Hjpxzoum3uC2l1MQQIm6ic796KcYWT/view?usp=share_link
