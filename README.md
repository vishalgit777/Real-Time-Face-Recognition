# Real-Time-Face-Recognition
Through this project, a  basic form of face recognition has been implemented using the Haar Cascades Classifier, openCV and K-Nearest Neighbors Algorithm.

Technologies Used:-

1.Opencv2:- is used here for reading & writing images and also to input a video stream.

2.Python :- Used various python libraries such as Numpy,Pandas.

we have created a real time selfie dataset using a Python Script that captures images from your webcam video stream.Then we have extracted all Faces from the image frame (using haar cascades) classifier.Then Flatten the largest face image(gray scale) and save it in a numpy array. and  have repeated the above for multiple people to generate training data.

For testing we have read a video stream using opencv,extract faces out of it and have used KNN algorithm to find the prediction of face. and then display the predictions on the screen — bounding box and name.


