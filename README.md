# **Finding Lane Lines on the Road** 

## Project for Udacity

### This project is the first touch with the technology behind self-driving car. 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. 

My pipeline consisted of few steps. First, I blurred image using gaussian filter with kernel size of 7.
In the next step, blurred image was converted into greyscale. Then, I used edge detector, where I used high/low treshold of 3.



### 2. Identify potential shortcomings with your current pipeline


Potential problems can come, when curvature of the line is too high or lanes are not seen at all.


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to have other markers than lines ... for example, we can
follow path of other cars in front of us.

Another potential improvement could be to use neural networks to get the lane detection
