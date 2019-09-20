# Self-Driving-Car
We built a model which had the capability of detecting Objects, Lanes and Stop signs.
Self Driving car has become a hot topic. This year Tesla launched Car with AutoPilot which has a capability of driving from point A to Point B. Not only Tesla but many of the companies like Google and Uber have invested heavily on Self Driving car. But before this we need to answer the question “ what’s the need of Self Driving car?”. The answer to that is very simple humans are susceptible to errors but sophisticated machines are less  susceptible to errors and on the roads a small mistake has a big impact. 
This project involves a car which is capable of taking decision like skipping the lane and stopping when a stop sigh is seen. This model car runs with the help of a battery and the power supply and validated by the raspberry pi attached to the car which gives the instruction. When there is an obstacle ahead of the car, it takes right and after taking right if still there is obstacle then it takes left and after taking left if the obstacle still exists then the car automatically stops. Now moving to the computer vision aspects, the model is trained with for the basic objects like stop signs, faces etc which has an accuracy of 87 percent depending.

Stop Sign Detection 
Image Processing is a key field that is used in many technologies. We started with collecting the images of different stop sings and once we thought we had enough we started training our model. We trained until we reached 80 percent accuracy. Raspberry pi is a low end computer it doesn’t have a lot of processing power so while training it took us some time. 
The objective was take a picture every 2 seconds and search for stop sign if found stop the car for n seconds.

Lane Detection
We used image processing for this one also we feed the computer with videos of lane and finally after training once we were able to detect lanes we integrated it with our ultrasonic code. When we detect a lane on the right side adjust the movement of the model. If the model is on the correct path then move forward. It was a tiring process to work on raspberry pi because it took a lot of time. 

StopSignDetection.py detects the stop signs and DistanceDetectio.py gives the distance between two objects. 


This google drive link provides you with the elaborate explaination of the project 
https://drive.google.com/file/d/12jaMQrN-0JQDMVCTNuxEBc9bsetKYWEO/view?usp=sharing
