# Project 2: Image Stitching

## Introduction
Image stitching is useful when creating an image with larger field of view (FOV) by stitching a set of images altogether. A common application of image stitching is to create a panorama, which has a wide-horizontal-angle view. In this project, we implemented an end-to-end algorithm, with input as a set of images, and with the output being the panorama of these images.

#### Feature Detection
- Mutil-Scale Oriented Patches 

#### Feature Matching 
- KNN Search

#### Cylindrical Projection
- Inverse Warping

#### Image Matching
- RANSAC Algorithm

#### Blending
- Linear Blending
- Multiband Blending

#### Rectangling
- Seam Carving

## Usage

1. Clone from [here](https://github.com/awinder0230/2017-Spring-Digital-Visual-Effect) if you do not have our codes.

2. Change directory to input_image, put your input images inside as well as a txt file with the format as following:
- Line 1: <number of input images>
- Line 2: <file name of first input image> <space> <focal length of this input image>
- …
- Line N+1: <file name of Nth input image> <space> <focal length of this input image>
Note that the first input image must be the one that you hope to be the leftmost image in your panorama.

3. Change directory to /src, open main.m with Matlab and run.

4. The output panorama will be generated under directory /result.

## More
More information in Resource/report.pdf
