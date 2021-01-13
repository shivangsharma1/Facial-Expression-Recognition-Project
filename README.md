# Facial-Expression-Recognition-Project

In this project, I have build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I have used OpenCV to automatically detect faces in images and draw bounding boxes around them. Once I have trained, saved, and exported the CNN, I have serve the trained model predictions to a web interface and perform real-time facial expression recognition on video and image data.

## Dataset
The dataset I have used in this project is the FER 2013 dataset. The dataset is freely available on the net, so I not providing any preferable link.

Sample video I have used in this project: [link](https://drive.google.com/drive/folders/1544B3kdXWqLbElMnpgF9Au4oNPezjkdJ?usp=sharing)

## IF you want to replicate the project.

Make sure to install dependencies using pipenv with the provided Pipfile and execute all commands using pipenv. Also, please make sure to add the correct path to the video file in camera.py on line 11. Next, to install pipenv, the dependencies, and run the main.py file, execute the following commands from your terminal or command prompt, making sure to add the right paths where necessary:

* cd \path\to\Project\
* pip install pipenv
* pipenv install
* pipenv run python3 main.py
