# OpenCV-Project
Gesture Volume Control Software For Windows

## Technologies Used
Python    : Programming language  
OpenCV    : To capture webcam input  
Mediapipe : To detect, track hands  
Pycaw     : To control system volume on Windows  

## Description  
1) In this project I have build a gesture volume control system which will allows us  to control the volume of the computer by just using two fingers.  
2) This software captures your webcam input, detects focal points on your hand like the fingertips and joints and allows us to find the distance between two points.  
3) To build this app we use opencv's python module which allows us to capture video from our web cam, frame-by-frame.  
4) Once the video is captured then MediaPipe is used which provides us a set of already trained machine learning models which allows us to detect hands in a live video. 
5) Then detecting the key points on our hands to detect a gesture and find the distance between tips of two fingers so that we could control system volume.   
6) At last using pycaw on Windows to control the system volume and integrate the two things together so that volume could be controlled by two fingers.

## Installation
1) Python x.x < Python 3.9
2) OpevCV

```bash
  pip install opencv-python
```
4) Mediapipe (pip install will currently not work with versions >= 3.9)

```bash
  pip install mediapipe
```
5) Pycaw (Pyton Core Audio Windows Library)

```bash
  pip install pycaw
```

## How to RUN the PROJECT
### Follow the following steps  
1) Open the python file given in the repo, install all the requirement using pip commands.
2) Make sure web camera is working fine to capture the hand.
3) Slowly take your index finger and thumb to control the volume of the system. 
4) If we increase the distance between the these two fingers --> it will increase the volume.
5) If we decrease the distance between the these two fingers --> it will decrease the volume. 
6) Enjoy :smile:

## KEY CONCEPTS  
### OpenCV
* OpenCV (Open Source Computer Vision) is a free and open-source library of computer vision and machine learning algorithms for image and video processing. It was developed by Intel in 1999 and is now maintained by a community of developers.
* OpenCV is written in C++ and has interfaces for several programming languages, including Python, Java, and C#. 
* It is widely used in computer vision applications, such as object recognition, face detection, and image and video analysis. It is also commonly used in robotics, surveillance systems, and medical image analysis.
* Overall, OpenCV is a powerful and versatile tool for computer vision and machine learning tasks, and it is widely used in a variety of applications.

### MediaPipe
* MediaPipe is an open-source framework developed by Google for building multimodal (i.e., involving multiple modalities such as audio, video, and text) machine learning pipelines.
* It is designed to make it easy for developers to build and deploy complex multimodal ML models for tasks such as object detection, face recognition, and language translation.
* MediaPipe is written in C++ and provides a set of pre-built, reusable components called "Calculators" that can be combined to build custom ML pipelines. These Calculators can perform a variety of tasks, such as video and audio decoding, image processing, and machine learning inference. 
* MediaPipe also includes a set of tools for training and evaluating ML models, as well as for deploying them in production environments.
* Overall, MediaPipe is a powerful and flexible framework for building and deploying multimodal machine learning models, and it is widely used in a variety of applications such as augmented reality, robotics, and natural language processing.

#### Mediapipe HANDS (Used in Project)
* MediaPipe Hands is a high-fidelity hand and finger tracking solution. It employs machine learning (ML) to infer 21 3D landmarks of a hand from just a single frame.
* It uses Hand Landmark Model for performing precise keypoint localization of 21 3D hand-knuckle coordinates inside the detected hand regions via regression, that is direct coordinate prediction. The model learns a consistent internal hand pose representation and is robust even to partially visible hands and self-occlusions.  

![image](https://user-images.githubusercontent.com/102078863/208759480-c9010c2f-bc56-4557-ab1d-63cd888f577c.png)  

![image](https://user-images.githubusercontent.com/102078863/208759502-5ef1707e-c82a-4175-ba2d-2ea996dfacc7.png)

### OpenCV vs Mediapipe
* Focus: OpenCV is primarily focused on image and video processing, while MediaPipe is focused on building multimodal machine learning pipelines (i.e., involving multiple modalities such as audio, video, and text).
* Functionality: OpenCV provides a wide range of tools and functions for image and video processing, including image filtering, morphological operations, color space conversion, edge detection, and object tracking. It also includes machine learning algorithms for training and predicting models on image and video data. 
* MediaPipe, on the other hand, provides a set of pre-built, reusable components called "Calculators" that can be combined to build custom ML pipelines, as well as tools for training and evaluating ML models and deploying them in production environments.
* Overall, OpenCV and MediaPipe are both useful tools for building computer vision and machine learning pipelines, but they have different focuses and functionality. OpenCV is more general-purpose and is primarily focused on image and video processing, while MediaPipe is specifically designed for building multimodal machine learning pipelines.

## THANKYOU FOR VISITING :smile:


