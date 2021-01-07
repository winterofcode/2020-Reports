<center><a href="https://winterofcode.com/"><img src="https://camo.githubusercontent.com/c73f77959233a8adb69f3dee7bbb3ba5e016f4239c7496c82538cc60c984f56e/68747470733a2f2f77696e7465726f66636f64652e636f6d2f7374617469632f6d656469612f6f72672d6c6f676f2e39333564376634382e706e67" alt="gsoc" height="50"/></a>
<a href="https://www.python.org/"><img src="https://www.python.org/static/community_logos/python-logo.png" height="45"/></a>
<a href="#"><img src="https://i.ibb.co/0rjmMyS/header.jpg" alt="header" border="0"></a>
</center>

# Developer - Winter of Code 2020
* **Name:** Abhinav Chauhan
* **Organisation:** DSC - NSEC
* **Project:** [DocScanner](https://github.com/dscnsec/DocScanner.git)

## Language Used
* Python

## Library Used
* OpenCV
* Numpy

## There are Following Steps:-
## Reading image using OpenCV
<img src="https://i.ibb.co/ng1d8dG/1.jpg" alt="Original Image" height="250"/>

## Image Preprocessing
* Converting orginal image to grey color
* Converting grey image to blurred image using Gaussian Blur
* Detecting edges using canny edge detector
* dilation and erosion of inage for better contour detection.
<img src="https://i.ibb.co/QpgH0d7/Threshold.jpg" alt="Preprocessed Image" height="250" >


## Contour Detection
* He we handle all the contour Detected and keep only the one with the greatest contour area.
* After getting that contour we draw a bounding box around it for visualisation and keep the coordinates of the corners of the required contour detected.
<img src="https://i.ibb.co/ZcLfYKR/Conttour.jpg" alt="Contour corner points" height="250" >

## Reorder coordinates
* This is the main function that resolves the issue posted in the repo. i.e to get corret order of the corner points of the contour detected.
* Arranging the corner coordinates in the correct order for Wrapping function at realtime using simple numpy library and basic arithmetic functions.

## Wrapping the Image
* In this step we wrap the image with the ordered points i.e. (0,0) (width, 0) (0, height) and (width, height) which we got from the reorder function.

## Result Image
* Here we diplay the the final scanned image.
<img src="https://i.ibb.co/Jz4kwCZ/Scanned.jpg" alt="Scanned output image" height="250" >

## Link To My Pull Request
https://github.com/dscnsec/DocScanner/pull/5

## Future Scope
* Working in the project of DocScanner not only we got more application in machine learning but we also got more intents towards different arean of computer vision.

## Overall Experience
* It was great exprience for me to got into Open Source culture through this great program and I would love to encorage more students to do this program in future.
