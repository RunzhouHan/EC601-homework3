# Exercise 4

## 1.Look at Threshold.cpp and implement the code in Python, and observe the results for different threshold values. Comment on the results.

truncate: Compare gray with threshold(127), change value above 127 to 127. Weakened the contrast.
binary: Compare gray with threshold(127), change value above 127 to 255, below 127 to 0. Enhanced the contrast.
band: Compare gray with threshold1(27), change value above 27 to 255, below 27 to 0. 
	  Then compare gray with threshold1(125), change value above 125 to 0, below 125 to 255. 
	  Bitwise and the two results. Because threshold1 and threshold2 are different in values, we get some bands to represent image infomation.
	  Image inverts black and white, and lost some information.
semi: The algorithm automatically computes the threshold of bimodal image, change value above threshold to 0, 		  and output none zero part. Decrease the variance of contrast.
adaptive： the algorithm calculate the threshold for a small regions of the image. So we get different thresholds 		for different regions of the same image. Compare gray with threshold(127), change value above 127 to 255, 		   below 127 to 0. Keep most of original information, Enhanced the contrast.


## 2.What are the disadvantages of binary threshold?

Single threshold may lose a lot of infomation in original image. 

## 3.When is Adaptive Threshold useful?

Tt gives us better results for images with varying illumination.

