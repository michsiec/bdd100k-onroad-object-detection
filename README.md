# Applying Computer Vision Algorithm for Object Detection in Autonomous Driving

## Aims and objectives
The aim of the project is to develop a computer vision software using deep learning techniques 
that is able to perform real-time object detection in different driving conditions.
In order to achieve the aim of the thesis, state-of-the-art YOLOv4 object detection system has
been implemented using Python frameworks: Darknet and OpenCV. It has been trained on large 
autonomous driving dataset, consisting of 70,000 annotated images, captured during driving in 
different traffic conditions.
Next, it was evaluated using validation and testing data. I have also experimented with testing the 
object detector on the video data collected by myself by an on-board car camera. The results has 
shown that the object detection training and evaluation has been accomplished successfully, and 
the software achieved good performance values for the most important classes of object on the 
road, that is vehicles, traffic signs and pedestrians

## Data
BerkeleyDeepDrive100K (BDD100K) is an open-source dataset for autonomous driving that consists of 100,000 HD videos that were recorded under different road and weather conditions, as well as at different times and seasons (Yu et al. 2020). Each video lasts about 40 seconds, has 720p resolution at 30 frames per second. 
The data collection was done in four different locations (of which three are in the vicinity of each other), that is: 
San Francisco, Berkeley, Bay Area, and New York. The areas of data collection have been illustrated below: 

![image](https://user-images.githubusercontent.com/96207926/207092396-b36e2462-9996-4fab-8168-5794445d5572.png)

The dataset contains extensive annotations regarding the weather type, scene, hours, therefore it can be used for many learning tasks, including object detection, various types of segmentation, lane marking, object tracking, pose estimation, etc.

The data and annotations can be obtained [here](https://bdd-data.berkeley.edu/) after logging in and agreeing to the BDD100K license. 
The authors provided the data available for downloading in different subsets, depending on particular task that one wants to undertake.
For example, it is possible to download 100,000 images, which are the frames at the 10th second in the videos, or download files that are dedicated for specific task
