# **Finding Lane Lines on the Road** 

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road

# Pipeline
<br>1) Convert to greyscale
<br>2) Gaussian Blur to add smoothing
<br>3) Canny Edge Detection
<br>4) Narrow the region of interest
<br>5) Hough Transform for line detection
