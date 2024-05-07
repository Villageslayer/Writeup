

# #Introduction

With the Rise in Popularity of Image Recognition Machine Learning(ML) and Consumer graphics cards getting Faster as well as including Special Tensor processing Cores, ML became accessible to the Masses. 

## This begs the following question: 
### Is this Fast enough to use it in First Person Shooters (FPS) to Assist the Player in aiming at the Enemy?

But I'm Getting Ahead of myself, let's start at the front of the Question.

# High Level Questions:
- ## Q: Is it Fast? 
 - ### A: Yes*
	*but very resource intensive.
- ## Q: Is it more accurate than a human Player?
	- ### A: I don't know that's what I want to find out.
- ## Q: Does it move Human or just snap to the Enemy?
	- ### A: The ML Model does not move it simply Detects the Enemy on Screen.


# But How  Does the Model know where the Enemy is and Who they are?

## Lets break down this question into it's parts

### How?: 
	Through a sub category of Image recognition that's known as ObjectDetection. 
### Who? :
	good Question.
### Where?: 
	If the Model Detects an Object it returns the Coordinates as [xmin,ymin,xmax,ymax]
### How does the Model Know?:
	Simple Answer: Training


# #Training?, ObjectDetection?, 

## What is ObjectDetection?:

	ObjectDetection describes the process of detecting an Object inside an Image and returning it's Coordinates

## #Training?:
	waste 100s of hours of your life drawing Rectangles on images.
	see #Training for more information.


# #Model?

	Ahh the Model, in this project I'm going to work with YouOnlyLookOnce or better known as YOLO more specifically YOLOv8

See https://docs.ultralytics.com/models/yolov8/ for Official Documentation

