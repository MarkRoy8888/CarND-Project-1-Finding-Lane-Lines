# **Finding Lane Lines on the Road** 



**Finding Lane Lines on the Road**

The goals / steps of this project are the following:

* Make a pipeline that finds lane lines on the road

* Draw a perfect line to find lane



### Reflection

### 1. modified the draw_lines() function.

I follow the homework suggest to handle the code.
In the end, I need improve "draw_lines" function to draw a better line.

My pipline have 5 steps,

1.gray : finding the line,so just to find the change of brightness, convert to gray.
2.canny : finding the edge, use canny method to find edge.
3.gaussian_blur : avoiding too many information, use gaussian to blur.
4.draw_lines : the new function separate right and left to reduce the noise.
5.hough_lines : to find the line.


### 2. Identify potential shortcomings with your current pipeline

I think some points can improve the process.

1.color : the third video, we can see the yellow is obvious, but in gray process I lose the information.

2.customized : the different have different camera postion, I find adjust some parameter for specific car.

### 3. Suggest possible improvements to your pipeline

1.handle the color

2.automate to adjust the camera position 
