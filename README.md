# Face-Expression-Recognition-using-Keras

In this repository I have built and trained a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions.
The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into
one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I have used OpenCV to automatically detect faces 
in images and drew bounding boxes around them. After trained, saved, and exported the CNN, it will directly serve the trained model predictions 
to a web interface and perform real-time facial expression recognition on video and image data.

![model](https://user-images.githubusercontent.com/55172199/89615220-73bcca80-d8c9-11ea-8cad-0a679f6f2ee3.png)
