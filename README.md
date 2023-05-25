# Driver's Drowsiness Detection & Alert System

Over 91,000 traffic incidents were caused by sleepy driving, according to the CDC, which estimates that 1 in 25 drivers (18 years of age or older) fall asleep behind the wheel. In order to prevent these problems, we’re going to develop a driver’s drowsiness detection and alerting system to avoid such a mess. As a result, Python enables the model of the deep learning algorithm through the use of OpenCV.

In this Python project, we’ll use OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. 

#
![Project](https://github.com/riyaz-shaiks/Driver-Drowsiness-Detection-and-Alert-System-Python-Deep-Learning/assets/133764680/24b7a2d2-1bec-4aa2-85c6-b761504074a8)


#
When you run the code it will open the webcam and start capturing the video and gives output based on the eyelid closure. Here we set the timer for 2.5 seconds and 5 frames per second. If the eyes were closed for 2.5 seconds continuously that means the model captures continuously 10 closed eye frames then it will alert the driver by beeping the alarm sound.



Our primary goal is to create a user-friendly software that can identify users whose eyes have been closed for an extended period of time and alert them. It can be helpful in many industries, including medicine and safety, which can benefit from this discovery.
