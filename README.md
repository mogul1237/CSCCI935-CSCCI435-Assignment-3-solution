# CSCCI935-CSCCI435-Assignment-3-solution

Download Here: [CSCCI935/CSCCI435 Assignment 3 solution](https://jarviscodinghub.com/assignment/cscci935-cscci435-assignment-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Objective
Design a C/C++ program that extracts moving objects from video using OpenCV library (Version 3.0 or higher).
Tasks
Extraction of moving objects from a sequence of images or video is often used in many video analysis tasks. For instance, it is a key component in intelligent video surveillance systems. In this assignment, you are required to develop a program in C/C++ using OpenCV (v3.0 or higher) to detect, separate and label all moving objects from a given sequence of images or video which has been captured by a stationary camera. There are three key steps involved in the extraction of moving objects from video captured by a stationary camera:
1. Detection of moving pixels using background modelling and subtraction;
2. Removal of noisy detection using morphological operators or majority voting and;
3. Labelling of separate moving objects using connected component analysis.
OpenCV 3.0 provides various algorithms for each of steps 1 & 2. However, you may have to implement your own connected component analysis algorithm. For simplicity, you may assume that each connected component forms one object. The program should display the original video frames; detected moving pixels after the background modeling and subtraction; the moving pixels after morphological operations or majority voting and; the detected moving objects in a single window as illustrated below (see Table 1). The detected object has to be colour-coded, that is, objects (i.e. connected components) are displayed in diﬀerent colours. You also need to produce a one-page report (my-login-name-report.pdf) that describes your implementation of each step, choice of the algorithms at each step and how the parameters for the chosen algorithms are set.
1
Original Video Frame Detected Moving Pixels
Moving pixels after ﬁltering Detected object (colour-coded)
Table 1: Organization of output window
Requirements on coding
1. The program should be named as mvDetection and shall take an image ﬁle as the input video, e.g. mvDetection videofile.
2. You may develop your code using Visual Studio. You need to submit the source code EXCLUDING all binary ﬁles. The submitted code must be able to compile using any standard-compliant C++ compiler.
3. No other third-party libraries should be used in the program except OpenCV 3.0 (or higher). The code has to be in C/C++.
Submission
You are required to create a folder (suitably named: my-login-name) in which you place your source code and one-page report. Compress the folder using zip or rar and name it my-login-name.zip(.rar). On the Moodle site for the subject you will ﬁnd Assignment-3 submission drop box.
Marking Scheme
1. Zero marks may be awarded if your code cannot be compiled on a standard-compliant C++ compiler.
2. Program structure, comments and usability (2%)
3. Read and display of the video image (3%)
4. Background modeling, subtraction and display of the detected moving pixels (5%)
5. Filtering of the detected moving pixels and display of the result (5%)
6. Connected component analysis and display of the color-coded objects (3%)
7. Report (2%)
2
References
1. Robert Laganiere, “OpenCV 2 Computer Vision: Application Programming Cookbook”, 2nd Edition, Chapter 6, 11.
2. Gary Bradski and Adrian Kaehler, “Learning OpenCV”, Chapter 9.
