# Computer Vision
Assignments for computer vision courses introduced by Dr. Marwan Torki

## Assignment 1
### Part I: Applying Image Processing Filters For Image Cartoonifying
In this part of the assignment we want to make the real-world images look like they are genuinely
from a cartoon. The basic idea is to fill the flat parts with some color and then draw thick
lines on the strong edges. In other words, the flat areas should become much more flat and the
edges should become much more distinct. We will detect edges and smooth the flat areas, then
draw enhanced edges back on top to produce a cartoon or comic book effect.

 <p align="center">
<img src="https://github.com/AbdelrahmanSalem9/computer-vision/blob/master/Assignment%201/Part%20one/Test%20images/Output%201.png" width="500" height="400">
  </p>

### Part II: Road Lane Detection Using Hough Transform
The objective of this part of the assignment is the detection of road lanes in an image using Hough Transform.
 <p align="center">
<img src="https://github.com/AbdelrahmanSalem9/computer-vision/blob/master/Assignment%201/Part%20two/Test%20images/Output%202.png" width="900" height="300">
  </p>
  
## Assignment 2
### Part I:Augmented Reality with Planar Homographies
In this assignment, you will be implementing an AR application step by step using planar homographies. You will first learn to find point correspondences between two images and use these to estimate the homography between them. Using this homography you will then warp images and finally implement your own AR application.
You will be provided with book.mov (Figure 1.a) and ar source.mov (Figure 1.b). Our Final goal is to overlay each frame of ar source.mov onto the book in book.mov like the result in (Figure 1.c) and create your new video from these overlay frames.
 <p align="center">
<img src="https://github.com/AbdelrahmanSalem9/computer-vision/blob/master/Assignment%202/Part%201/data/Output.png" width="700" height="400">
  </p>
  
### Part II: Image Mosaics
In this part of the assignment, you will implement an image stitcher that uses image warping and homographies to automatically create an image mosaic. We will focus on the case where we have two input images that should form the mosaic, where we warp one image into the planeof the second image and display the combined views. original input.
 <p align="center">
<img src="https://github.com/AbdelrahmanSalem9/computer-vision/blob/master/Assignment%202/Part%202/data/Output.png" width="700" height="400">
  </p>

## Assignment 3
### Part I: Stereo Vision
In this part of the assignment you will implement and test some simple stereo algorithms. In each case you will take two images Il and Ir (a left and a right image) and compute the horizontal disparity (ie., shift) of pixels along each scanline. This is the so-called baseline stereo case, where the images are taken with a forward-facing camera, and the translation between cameras is along the horizontal axis. We will calculate the disparity using two ways.
<p align="center">
<img src="https://docs.opencv.org/4.x/disparity_map.jpg" width="900" height="300">
  </p>

### Part II: Tracking Objects in Videos
You will implement the Lucas-Kanade tracker, where two video sequences are provided: a car on a road, and a helicopter approaching a runway link. To initialize the tracker you need to define a template by drawing a bounding box around the object to be tracked in the first frame of the video. For each of the subsequent frames the tracker will update an affine transform that warps the current frame so that the template in the first frame is aligned with the warped current frame.
<p align="center">
https://user-images.githubusercontent.com/88258538/221055012-e5c2bfff-8e32-429e-8ed9-3a05797e75f0.mp4
</p>

## Assignment 4
### Object Detection
In this assignment, you will work on Cocco dataset which is a large-scale object detection, segmentation, and captioning dataset. You are required to run 3 different object detectors on this dataset. We will learn to use and differentiate between the architectures.




