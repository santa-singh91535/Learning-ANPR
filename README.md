# Project Name :Automatic number plate Recognition 
# Description :
Automatic number plate recognition (ANPR) is a technology that automatically identifies and extracts the license plate number from an image or video. ANPR systems are used in a variety of applications, such as traffic monitoring, law enforcement, and parking enforcement.
This project is an implementation of an ANPR system using the Python programming language and the OpenCV library. OpenCV is a powerful computer vision library that provides a number of functions for image processing and object detection.
The ANPR system in this project uses a two-step approach to license plate recognition:
License plate detection: This step involves identifying the region of the image that contains the license plate.
License plate recognition: This step involves extracting the license plate number from the detected region.

The license plate detection step uses a sliding window approach. A sliding window is a rectangular region that is moved over the image. The license plate detection algorithm compares the pixels in the sliding window to a set of reference pixels that are known to be part of a license plate. If the similarity between the pixels is high enough, then the sliding window is considered to have found a license plate.

The license plate recognition step uses a machine learning model to recognize the license plate number. The machine learning model is trained on a dataset of images that contain license plates. The model learns to identify the features of license plates, such as the shape, size, and font of the characters.
# Steps :
   1.install python ( with version compatible with Tensorflow)
   2.Make a virtaul environment ( using venv library , it is recommended to use virtual environment).
   3.Install CUDA and CUDnn to enable efficeint use of GPU( compatible with the Tensorflow version ).
   4.Install tensorflow model zoo.
