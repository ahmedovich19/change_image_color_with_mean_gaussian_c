# Implementing threshold and adaptiveThreshold on image

A diverse set of images, particularly those with varying lighting conditions, is crucial for understanding adaptive thresholding. This method helps in segmenting images in different light conditions, and a good dataset enables us to see its efficacy.

In this project apply adaptive thresholding using the mean threshold method (cv2.ADAPTIVE_THRESH_MEAN_C) to indicate that we are using the arithmetic mean of the local pixel neighborhood to compute our threshold value of T and we apply cv2.ADAPTIVE_THRESH_GAUSSIAN_C to indicate we want to use the Gaussian average.

By applying adaptive thresholding we can threshold local regions of the input image (rather than using a global value of our threshold parameter, T). Doing so dramatically improves our foreground and segmentation results.
