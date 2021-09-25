# Object-Recognition-using-YOLO-v3

### Here is a demo of the web deployment of this project, working on my local host.
![DEMO](https://user-images.githubusercontent.com/48491447/134743533-9da802a9-7dbe-4ea4-9c64-30e0181dd500.gif)

# Team :

- [Anirudh Singh Chauhan](https://www.linkedin.com/in/anirudh-singh-chauhan/)
- [Muskan Sanghai](https://www.linkedin.com/in/muskan-sanghai/)
- [Shantanu Gupta](https://www.linkedin.com/in/shantanu-gupta-b34689170/)

# Summary
Object detection is one of the classical problems in computer vision where you work to recognize what objects are inside a given image and also where they are in the image. The problem of object detection is more complex than classification. 

In object detection, we not only need to identify all the objects of interest in the image, but also their positions. The positions are generally represented by a rectangular bounding box.

With YOLO, a single CNN simultaneously predicts multiple bounding boxes and class probabilities for those boxes. YOLO trains on full images and directly optimizes detection performance. YOLO is popular because it achieves high accuracy while also being able to run in real-time.  
# Introduction

●	The modern world is enclosed with huge amount of digital information. To analyze and understand this huge information there exist image analysis techniques. 

●	Those methods that automatically recognize and detect the objects prove to beat great use and provide a significant help in modern applications and devices.  

●	The important content of image is the object in the image. So there exists a significant and essential need for object recognition techniques.

●	Recognition is an important task in image processing and computer vision.

●	Object recognition refers to a collection of related tasks for identifying objects in digital photographs.
1.	Image classification :  involves predicting the class of one object in an image
2.	Object Localization : process to identifying the location of one or more objects in an image and drawing abounding box around their extent.
3.	Object Detection : it combines these two tasks and localizes and classifies one or more objects in an image.

●	Region-Based Convolutional Neural Networks, or R-CNNs, are a family of techniques for addressing object localization and recognition tasks, designed for model performance.

•	R-CNN is composed of two steps: 
1.	Using selective search, it identifies a manageable number of bounding-box object region ( region of intrest ).
2.	Then it extracts CNN features from each region independently for classification. 

# What Is YOLO?

•	You Only Look Once, or YOLO, is a second family of techniques for object recognition designed for speed and real-time use.

•	The approach involves a single neural network trained end to end that takes a photograph as input and predicts bounding boxes and class labels.

•	 The technique offers lower predictive accuracy (e.g. more localization errors), although operates at 45 frames per second and up to 155 frames per second for a speed-optimized version of the model.

•	The model works by first splitting the input image into a grid of cells, where each cell is responsible for predicting a bounding box if the center of a bounding box falls within it.  
![image](https://user-images.githubusercontent.com/48491447/134741624-7274b610-2c7d-4ae6-8bb3-929407e339ef.png)

•	Each grid cell predicts a bounding box involving the (x, y) coordinate and the width and height . Then feed it to the trained neural network.


# APPLICATIONS

●	This system can be optimized and can be used to develop various intelligent application which can be further used in many developing sectors such as agricultural, security, autonomous vehicle systems, etc.


 ![image](https://user-images.githubusercontent.com/48491447/134741657-e432628d-88ff-4dd9-be37-beebe146c31a.png)

