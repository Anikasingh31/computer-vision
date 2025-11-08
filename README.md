# computer-vision

Unit-1

Image Smoothing, Sharpening, and Edge Detection

Dataset: Kaggle - LISA Traffic Sign Dataset (UCSD)

Image enhancement techniques are used to improve the visual quality of images. Filtering is one of the most common enhancement methods, achieved using convolution operations.

Smoothing filters (like Gaussian blur) remove noise.

Sharpening filters (like Laplacian) enhance edges.

Edge detection filters (like Sobel or Canny) highlight boundaries and features.

unit 2

Connected component labeling is a classic image processing technique that detects, labels, and counts distinct objects in a binary image. We’ll use thresholding to create a binary mask, morphological operations to clean noise, and cv2.connectedComponents to label each object.

UNIT 3

The Hough Transform is a powerful algorithm used to detect geometric shapes such as lines and circles in an image.

The Hough Circle Transform converts edge pixels into a parameter space (center (x, y) and radius r).

Peaks in this space correspond to possible circles.

It’s robust to noise, lighting variations, and partial occlusion.

Mathematically, each edge point votes for all possible circles passing through it using (x−a)2+(y−b)2=r2

and accumulates votes in a 3-D parameter space (a, b, r).

Unit-4

Optical Flow – Lucas-Kanade Method Optical Flow refers to the apparent motion of brightness patterns in an image sequence, caused by relative motion between the camera and scene.

The Lucas–Kanade method is a differential, local optical flow algorithm that estimates motion vectors for small feature points between consecutive frames by assuming:

The motion of neighboring pixels is constant within a small window.

Brightness of a pixel remains constant between frames.

This method is widely used for object tracking, motion analysis, and video stabilization.

Dataset: OpenCV’s sample videos

unit 5

Face Recognition using Eigenfaces Eigenfaces is a classic face recognition technique based on Principal Component Analysis (PCA). It projects face images into a lower-dimensional “face space” where each image is represented by a combination of eigenvectors (called eigenfaces). Recognition is done by comparing the projection of a test image to the projections of known images.

Dataset: AT&T ORL Faces Dataset (40 people × 10 images each)
