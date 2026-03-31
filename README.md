# Canny Edge Detection
Canny edge detection is an image processing method used to detect edges in an im-
age while suppressing noise.It extracts useful structural information from different
vision objects and dramatically reduce the amount of data to be processed. It has been
widely applied in various computer vision systems. Canny has found that the
requirements for the application of edge detection on diverse vision systems are
relatively similar.
It involves following steps :
1. Noise reduction
2. Gradient calculation
3. Non-maximum suppression
4. Double threshold
5. Edge Tracking by Hysteres
   
It is also known as the optimal edge detector :

1. The first criterion should have low error rate and filter out unwanted
information while the useful information preserve.

2. The second criterion is to keep the lower variation as possible between the
original image and the processed image.

3. Third criterion removes multiple responses to an edge.

   
First of all convert the image to gray-scale. Perform a Gaussian blur on the
image.The gradients can be determined by using a Sobel filter. The image magnitude
produced re- sults in thick edges. Ideally, the final image should have thin edges. Thus,
we must perform non maximum suppression to thin out the edges.After that I
performed an edge tracking algorithm to remove weak edges. Weak edges that are
connected to strong edges will be actual/real edges. Weak edges that are not connected
to strong edges will be re- moved. I performed this using DFS technique.

# Output and Intermediate Image format :

1. Gradient Magnitue
2. Gradient Direction
3. Thinned Image
4. Canny Output
