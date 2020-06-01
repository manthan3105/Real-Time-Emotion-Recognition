# Real-Time-Emotion-Recognition
Real-time face detection and emotion/gender classification using fer2013/IMDB datasets with a keras CNN model and openCV.

Real-Time Emotion Recognition

Comprises of two-step process i.e. face detection
(bounded face) in image followed by emotion detection
on the detected bounded face. 

I.
Haar feature-based cascade classifiers ​ : Quick
and robust Real-Time algorithm that face in a
video. Faster in comparison to other face
detectors. 

II.
Xception CNN Model ( ​ Mini_Xception, 2017 ​ ) ​ : We
will train a CNN model architecture that takes
bounded face (48*48 pixels) as input and predicts
probabilities of 7 emotions in the output layer.

# Dataset 

One can download the facial expression recognition (FER) data-set from Kaggle challenge here (https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). The data consists of 48×48 pixel gray scale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

The training set consists of 35,888 examples. train.csv contains two columns, “emotion” and “pixels”. The “emotion” column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The “pixels” column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order
