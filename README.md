# intruder-detection
Welcome to the repository of the OpenCV Intrusion Detection System, a sophisticated tool designed to enhance security by monitoring surveillance video streams for unusual activities. This system not only identifies intrusions but also archives relevant video segments for further analysis and can trigger alerts to notify security personnel.
# Why This Project is Important
In today's world, the safety and security of physical spaces are paramount. This project leverages computer vision and machine learning to provide a vigilant, always-on watch over sensitive areas, ensuring that any unusual activity is promptly detected and addressed. It's particularly useful in settings such as banks, stores, and private properties.

# How It Works
Background Subtraction: Uses createBackgroundSubtractorKNN() to differentiate moving objects from the static background.
Noise Reduction: Applies erosion to the foreground masks to minimize noise, ensuring that motion detection is accurate.
Motion Detection: Analyzes the shapes in the video via findContours() to capture the contours of moving objects.
Intrusion Identification: Identifies potential intrusions by assessing the size and location of the largest moving object.
Alerts and Record-Keeping: When an intrusion is detected, the system saves the relevant video segment and can trigger an alert.

# Ensure you have the following installed:

Python 3.6+
OpenCV (opencv-python)
Matplotlib
IPython (for Jupyter functionality)
Moviepy
Imageio
Numpy
