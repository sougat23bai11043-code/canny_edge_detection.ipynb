# Canny Edge Detection
Canny edge detection algorithm is a widely used technique for identifying edges in images. Its efficiency and accuracy make it a crucial tool in applications such as lane detection, object recognition, image segmentation and more.

The Canny edge detection algorithm is structured as a multi-stage process, each step essential for producing clean and continuous edges. Its steps are:
Noise Reduction Using a Gaussian Filter
To prevent false detection caused by image noise, the algorithm first applies a Gaussian blur. This smoothes out minor intensity variations making true edges more prominent.

The Gaussian kernel used is typically 5×55×5 with a standard deviation (
σ
σ) of 1.4
The kernel must be normalized so its values sum to 1.
