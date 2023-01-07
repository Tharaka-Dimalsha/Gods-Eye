# God's Eye
Semester 5 - CS3282 - Industrial Computer Engineering Project
## Introduction
People and vehicle tracking is a very important job to law enforcement forces and it is a very tedious task to do in manual mode. God,s eye will take camera feeds from different angle and highlight the specific object and give it's path when possible.

![People Tracking](https://hackster.imgix.net/uploads/attachments/656811/image22-1_dr1WmSq01g.jpg?auto=compress&w=900&h=675&fit=min&fm=jpg)

## Issues to be addressed
* Background fluctuations
* Image noise
* Rain, snow, turbulence
* Illumination changes & shadows
* Providing real time system

## Proposed System
Below is a diagram which describes the implementation of the system

![System Architecture](https://ars.els-cdn.com/content/image/1-s2.0-S1047320319300392-gr1.jpg)

## Project Plan
Tasks/Applications to be implemented in upcoming weeks:
* Frame pre-processing
* Object detection
* Object extraction
* Feature extraction
* Object tracking sequence
* Object tracking algorithm

Weeks reserved for further testing (integration testing) and/or to catch up on any delays or failures in prior weeks.

## Steps to run the system
1. First, clone the repository:
   git clone https://github.com/Tharaka-Dimalsha/gods-eye.git
2. Install the required python packages:
   pip install -r ./requirements.txt
3. Download trained yolov3.weights:
   wget -P model_data https://pjreddie.com/media/files/yolov3.weights
4. Run Tracking code:
   python object_tracker.py

