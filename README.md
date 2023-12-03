**VirtualZoom: Computer Vision-Based Virtual Zooming Application
**
Overview**
**

<img width="1159" alt="Screen Shot 2023-12-03 at 10 35 24 PM" src="https://github.com/AYoussef00/VirtualZoom-Computer-Vision---Machine-learning/assets/33284639/72ecae12-16eb-48b4-a9fc-a5f4d749adff">


This repository contains a Virtual Zoom application that leverages computer vision to enable virtual zooming using hand gestures. The application utilizes the cvzone library for efficient hand tracking, allowing users to control the zoom level seamlessly through hand movements in front of a camera.

Features**
Dynamic Zooming: The application detects specific hand gestures to initiate virtual zooming. As the user performs the zooming gesture with both hands, the application adjusts the zoom level dynamically.

Scale Calculation: The system calculates the scale of zoom based on the distance between the centers of the user's two hands. This distance is continuously monitored, ensuring a responsive and intuitive virtual zooming experience.

Visual Feedback: Users receive visual feedback on the screen, indicating the current zoom scale. The application overlays a resizable image onto the camera feed, providing a visual representation of the virtual zoom.

Getting Started
Clone the repository:

Copy code
git clone https://github.com/<your-username>/virtual-zoom.git
cd virtual-zoom

**Install dependencies:
**


pip install -r requirements.txt
Run the application:

python virtual_zoom.py
Requirements
Python 3.x
OpenCV
cvzone
Usage

Launch the application and stand in front of the camera.
Perform the zooming gesture with both hands to initiate virtual zooming.
Observe the dynamic zoom level feedback on the screen.
Contributing
Contributions are welcome! Feel free to open issues or pull requests for bug fixes, improvements, or new features.


Acknowledgments
The application is built on the foundation of the cvzone library and OpenCV.
Special thanks to the contributors and the open-source community.
