# Real-Time-Face-Detection-
# What is Face Detection?
Face detection involves identifying a person’s face in an image or video. This is done by analyzing the visual input to determine whether a person’s facial features are present.

Since human faces are so diverse, face detection models typically need to be trained on large amounts of input data for them to be accurate. The training dataset must contain a sufficient representation of people who come from different backgrounds, genders, and cultures.

These algorithms also need to be fed many training samples comprising different lighting, angles, and orientations to make correct predictions in real-world scenarios.

These nuances make face detection a non-trivial, time-consuming task that requires hours of model training and millions of data samples.

Thankfully, the OpenCV package comes with pre-trained models for face detection, which means that we don’t have to train an algorithm from scratch. More specifically, the library employs a machine learning approach called Haar cascade to identify objects in visual data. 

# Intro to Haar Cascade Classifiers
This method was first introduced in the paper Rapid Object Detection Using a Boosted Cascade of Simple Features, written by Paul Viola and Michael Jones.

The idea behind this technique involves using a cascade of classifiers to detect different features in an image. These classifiers are then combined into one strong classifier that can accurately distinguish between samples that contain a human face from those that don’t.

The Haar Cascade classifier that is built into OpenCV has already been trained on a large dataset of human faces, so no further training is required. We just need to load the classifier from the library and use it to perform face detection on an input image.

# Step 1: Pre-Requisites
First, let’s go ahead and import the OpenCV library and load the Haar Cascade model

# Step 2: Access the Webcam
Now, need to access our device’s camera to read a live stream of video data.

# Step 3: Identifying Faces in the Video Stream
Now, let’s create a function to detect faces in the video stream and draw a bounding box around them

# Step 4: Creating a Loop for Real-Time Face Detection
Now, need to create an indefinite while loop that will capture the video frame from the webcam and apply the face detection function to it

After running the above code, you should see a window called My Face Detection Project appear on the screen.
