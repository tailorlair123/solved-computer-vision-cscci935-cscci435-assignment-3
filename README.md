Download Link: https://assignmentchef.com/product/solved-computer-vision-cscci935-cscci435-assignment-3
<br>
<h1>Objective</h1>

Design a C/C++ program that extracts moving objects from video using OpenCV library (Version 3.0 or higher).

<h1>Tasks</h1>

Extraction of moving objects from a sequence of images or video is often used in many video analysis tasks. For instance, it is a key component in intelligent video surveillance systems. In this assignment, you are required to develop a program in C/C++ using OpenCV (v3.0 or higher) to detect, separate and label all moving objects from a given sequence of images or video which has been captured by a stationary camera.

There are three key steps involved in the extraction of moving objects from video captured by a stationary camera:

<ol>

 <li>Detection of moving pixels using background modelling and subtraction;</li>

 <li>Removal of noisy detection using morphological operators or majority voting and;</li>

 <li>Labelling of separate moving objects using connected component analysis.</li>

</ol>

OpenCV 3.0 provides various algorithms for each of steps 1 &amp; 2. However, you may have to implement your own connected component analysis algorithm. For simplicity, you may assume that each connected component forms one object. The program should display the original video frames; detected moving pixels after the background modeling and subtraction; the moving pixels after morphological operations or majority voting and; the detected moving objects in a single window as illustrated below (see Table 1). The detected object has to be colour-coded, that is, objects (i.e. connected components) are displayed in different colours.

You also need to produce a one-page report (my-login-name-report.pdf) that describes your implementation of each step, choice of the algorithms at each step and how the parameters for the chosen algorithms are set.

<table width="433">

 <tbody>

  <tr>

   <td width="205">Original Video Frame</td>

   <td width="227">Detected Moving Pixels</td>

  </tr>

  <tr>

   <td width="205">Moving pixels after filtering</td>

   <td width="227">Detected object (colour-coded)</td>

  </tr>

 </tbody>

</table>

Table 1: Organization of output window

<h1>Requirements on coding</h1>

<ol>

 <li>The program should be named as mvDetection and shall take an image file as the input video, e.g. mvDetection videofile.</li>

 <li>You may develop your code using Visual Studio. You need to submit the source codeEXCLUDING all binary files. The submitted code must be able to compile using any standard-compliant C++ compiler.</li>

 <li>No other third-party libraries should be used in the program except OpenCV 3.0 (orhigher). The code has to be in C/C++.</li>

</ol>