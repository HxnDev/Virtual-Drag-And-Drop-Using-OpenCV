# Virtual Drag & Drog using OpenCV
In this project we will be using OpenCV to virtually drag a rectangle and drop it at a different location. It will be further used for [Virtual Mouse](https://github.com/HxnDev/Virtual-Mouse-using-OpenCV).

## Project Description: 
In this project, I am using the live feed coming from the webcam of my system to drag and drop a rectangle on the screen. I am detecting two things: hand and a click
Click will be detected when the fore finger and the middle finger come close to each other. We will create a rectangle on the screen and then drag it and drop it to a different location.

![Alt Text](https://github.com/HxnDev/Virtual-Drag-and-Drop-using-OpenCV/blob/main/Virtual%20Drag%20and%20Drop.gif)

## Requirements:
- cvzone
- mediapipe

## CVZone:
This is a Computer vision package that makes its easy to run Image processing and AI functions. At the core it uses OpenCV and Mediapipe libraries.

It can be installed using "pip install cvzone"

## Mediapipe:
MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) applied ML pipelines.

It can be installed using "pip install mediapipe"

## Important Note:
I faced some issues during this project. The issues and their solutions are as follows:
- FindPositon() not found: This is because you are running a newer version of cvzone. In newer versions, they removed findpositions and added findhands. So you need to install the version [cvzone v1.4.1](https://pypi.org/project/cvzone/1.4.1/). You could click the above link or simply use "pip install cvzone==1.4.1"

## Contact Information:
For any further queries, feel free to contact me at:

Email: chhxnshah@gmail.com 

LinkedIn : [Hassan Shahzad](https://www.linkedin.com/in/hassan-shahzad-2a6617212/)
