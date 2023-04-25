# Advanced-Lane-Lines-detection
In this project, I used Python and OpenCV to detect lane lines on the road. I developed a processing pipeline that works on a series of individual images, and applied the result to a video stream.

# The-Project
The goals / steps of this project are the following:

Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
Apply a distortion correction to raw images.
Apply a perspective transform to rectify binary image ("birds-eye view").
Use color transforms, gradients, etc., to create a thresholded binary image.
Detect lane pixels and fit to find the lane boundary.
Determine the curvature of the lane and vehicle position with respect to center.
Warp the detected lane boundaries back onto the original image.
Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.
The images for camera calibration are stored in the folder called camera_cal. The images in test_images are for testing your pipeline on single frames.

The challenge_video.mp4 video is an extra (and optional) challenge for you if you want to test your pipeline under somewhat trickier conditions. The project_video.mp4 video is another optional challenge and is brutal!

If you're feeling ambitious (again, totally optional though), don't stop there! We encourage you to go out and take video of your own, calibrate your camera and show us how you would implement this project from scratch!

# The-Environment
1) Windows 10
2) Google Colab
3) Python 3.10.10
4) OpenCV 4.7.0

# Conclusion
This program used to create a pipeline that can detects lane boundaries, predicts upcoming curves, and measures lane curvature.
