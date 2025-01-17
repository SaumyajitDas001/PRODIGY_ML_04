# PRODIGY_ML_03
A model that identifies and interprets human gestures using machine learning and computer vision.
The database is composed by 10 different hand-gestures (showed above) that were performed by 10 different subjects (5 men and 5 women). 
1.The different classes were:
2. palm
3. l
4. Index
5. Fist_moved
6. c
7. ok
8. down
9. thumb
10. palm_moved
11. Fist
This repository aims to classify hand gestures. There are various uses to it such as aiding communication for the deaf. It can also be used for gaming devices such as the Microsoft Kinect. Our dataset is comprised of infrared images obtained by a Leap Motion sensor. The dataset consists of 10 different hand gestures. There are 10 subjects, 5 male and 5 female. There are a total of 20000 images. Thus, an image should be classified into one of the 10 classes.
This repository builds a hand gesture recognition model using two approaches:
CNN based approach
Ensembled based approach
The main aim of this repository is to have a comparative study between the two approaches.
The first step in classification is preprocessing. Since the dataset was a collection of hand gesture images, detecting the hand was the first task. For detecting the hand, we used OTSU’s binarization technique and converted all the images into black and white images.
Principal Component Analysis(PCA) was done for the images and reduced to 4 dimensions for easier processing in emsembled approach.
The models that were considered for this approach are:
1.Stochastic Gradient Classifier
2. K Nearest Neighbour
3. Decision Tree
4. Random Forest Tree
Stacking and Voting Based Classifiers were used to combine the models
