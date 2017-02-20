### Reflection

###1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My first pipeline consists of eight different steps. At first the image gets converted to the HLS color space filter the different colors of the lane lines. I chose the HLS space because it is better suited for filtering colors and made the lanes stick out more than other color spaces. 
For detecting edges with Canny edge detection it is necessary to convert the new image to gray. By applying a Gaussian blur filter it further improves the detection.
To remove excessive lines I create a region of interest and override pixels outside of this region with zeros.
Possible lines get detected by a Hough transformation and 

![test image](./test_images/solidWhiteCurve.jpg)


###2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


###3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...