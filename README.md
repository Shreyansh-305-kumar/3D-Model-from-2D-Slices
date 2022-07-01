# 3D-Model-from-2D-Slices

• Over time, there have been various advancementsin the field of medical diagnosis.
• The focus has been increasingly shifting to diagnosis via 3D visualization of internal organs.
•The existing techniques are very expensive and hence we develop a cost-efficient model that can
create a 3D model out of our 2D dataset.

K means clustering is an unsupervised algorithm used to identify clusters in the
data. K means clustering can be used in image data to segment interesting areas
from the back- ground. It clusters given data into K clusters using the k
centroids.This algorithm is used when we have unlabelled data. The goal is to find
certain groups based on some kind of similarity in the data with the number of
groups represented by K.

Canny Edge Detection OpenCV provides cv2.Canny(image, threshold1, threshold2) function for edge detection.
The first argument is our input image. Second and third arguments are our min and max threshold
respectively. Using the Canny algorithm, the function discovers edges in the input image (8-bit input
picture) and marks them in the output map edges. For edge linking, the least value between threshold1 and
threshold2 is chosen. The biggest value is used to locate the beginnings of strong edge segments.

•It has been distributed in two Jupyter notebooks :
1. Pre-processing
2. 3D Visualization
