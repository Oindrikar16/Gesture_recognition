# Gesture_recognition
# Introduction
Hand gesture recognition is a crucial aspect of
human-computer interaction, enabling users to communicate
with devices naturally and intuitively. With the advancements
in deep learning, there is an opportunity to develop robust and
accurate systems for hand gesture detection. The primary goal of
this project is to design and implement a hand gesture detection
system using two approaches – CNNs and Ensembled Method
using different models like KNN, Decision Trees, Random Forest,
ANN and SVM. The system will be capable of recognizing a
variety of hand gestures, allowing users to interact with devices
in real-time. This will also be an asset for people with hearing
impairment and has a wide application in human-computer
interaction.

# Data Collection
A collection of near-infrared photos taken by the Leap Motion
sensor serves as the basis for the hand gesture recognition
database. 10 distinct hand gestures— 5 by women and 5 by
men—that were executed by ten distinct subjects make up the
database, which is displayed below.
The different classes were:
1) palm
2) l
3) Index
4) Fist moved
5) c
6) ok
7) down
8) thumb
9) palm moved
10) Fist
    
It can help the deaf communicate, among its many other
uses. Gaming devices can also be utilized with it. The infrared
photos in our dataset were captured using a Leap Motion
sensor. There are ten distinct hand gestures in the dataset.
Ten subjects total—five male and five female. There are
twenty thousand pictures in all. An image should therefore
be categorized into one of the ten classes.

Kaggle Dataset link: https://www.kaggle.com/datasets/gtiupm/leapgestrecog

# Data Preprocessing 
The process of classification begins with preprocessing.
The initial task was to identify the hand because the dataset
included pictures of hand gestures. After detecting the hand
using OTSU’s binarization technique, we black and white
converted each image.

OTSU’s Binarization Technique: Otsu’s method, also known
as Otsu’s thresholding or Otsu’s binarization, is a widely used
technique for image thresholding. It automatically determines
the optimal threshold value to separate the pixels of an image
into two classes: foreground and background.

The algorithm works by finding the threshold that minimizes
the intra-class variance or maximizes the inter-class variance
of pixel intensities in the image. This threshold separates the
image into two classes based on pixel intensity: foreground
(objects of interest) and background.

In order to facilitate processing, especially in the ensembled
approach, the images were subsequently reduced to four
dimensions and submitted to Principal Component Analysis
(PCA).A common dimensionality reduction method for reducing
the number of variables in big data sets is principal
component analysis, or PCA. This is accomplished by the
method by shrinking the initial set of variables while keeping
most of its data. Smaller data sets are easier to analyze and
visualize, and data point analysis becomes much faster and
simpler because machine learning algorithms have fewer extra
variables to process.

# Conclusion
This project investigates various machine learning algorithms,
such as Logistic Regression, Convolutional Neural
Networks (CNN), Artificial Neural Networks (ANN), KNearest
Neighbours (KNN), Random Forest, Support Vector
Machines (SVM), and Decision Trees in depth. The repository
intends to conduct a thorough comparative study of these
various approaches, shedding light on their respective strengths
and weaknesses in addressing specific tasks. The importance of
adopting a holistic strategy tailored to different business
domains, such as socially assistive robots and Virtual Reality,
is emphasised. By comparing and contrasting these algorithms,
the project hopes to provide insights into their applicability and
effectiveness across a wide range of applications, thereby
contributing to a more nuanced understanding of their utility in
a variety of real-world scenarios.
