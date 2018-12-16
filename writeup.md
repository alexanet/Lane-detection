# **Finding Lane Lines on the Road** 

This code is written in Python and has been tested for Python3 and opencv3.

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road


My pipeline consisted of 5 steps. 

1. I converted the images to grayscale.
2. Then I used gaussian blur to smooth the image.
3. Usung canny edge detection to detect the edges and is this step definig the low and high threshold is the key.
4. Defing the ROI (region of interest)
5. And finally apply hough lines to the ROI.
In order to draw a single line on the left and right lanes, I modified hough_lines() function by ...


### 2. Identify potential shortcomings with my current pipeline

My current piple works well and fast for straght line.


### 3. Suggest possible improvements for my pipeline:

Since the last video since it has different sizes min_y and vertices variables needs to be changed.

