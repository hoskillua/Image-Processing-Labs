<h1 align="center">
  Image Processing Labs
</h1>

# Overview

This repo is a collection of all image processing assignments completed using SK-image in python in fulfillment of an academic image processing course.

<br/>

## Lab 1 - Warm Up

A warm up lab on using SK-image functions and working with HSV colorspace and Histograms

<br/>

## Lab 2 - Frequency Domain

Working with frequency domain and conversions between it and Spatial domain. Also, Applying Filters by Convulotion

<br/>

## Lab 3 - Smoothing

Removing Salt & Paper Noise and Gaussian Noise; By Implementing Median and Gaussian filters.

<br/>

## Lab 7 - Thresholding

### 7.1 - Background/Foreground Segmentation

Using different thresholding conditions on the 3 channels of the image followed by morhphological operations we were able to segment:

1. the foregorund (golf ball and target)
2. the golf ball only

as shown below

<div align="center">
<img src="./Lab7/Highlights/output1.png" alt="Equation" style="width:800px;">
<img src="./Lab7/Highlights/output2.png" alt="Equation" style="width:800px;">
</div>
<br/>

### 7.2 - Changing a specific color in image

Using thresholding on the green color in the HSL color model (by an ellipsoid equation), we were able to select grass pixels and turn them into orange

as shown below

<div align="center">
<img src="./Lab7/Highlights/output3.png" alt="Equation" style="width:800px;">
</div>

<br/>

## Lab 8 - Adaptive Thresholding

Recursively splits image and applys thresholding to a local segment of the image. Some examples are shown below (left: input, middle: result of global thresholding, and right: local thresholding)

<div align="center">
<img src="./Lab8/Highlights/output1.png" alt="Equation" style="width:800px;">
<img src="./Lab8/Highlights/output2.png" alt="Equation" style="width:800px;">
</div>
