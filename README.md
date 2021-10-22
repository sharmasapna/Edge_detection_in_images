### Sobel Edge Detection¶
Steps:

1. Take a grayscale image
2. To get an output image of the same size , we pad the image with zeros
3. Convolve the image with the x and y kernels for Sobel, Sobel-Feldman, Scharr, Lapacian
4. Take the gradients for edge detection 
5. Final output

### image source : https://en.wikipedia.org/wiki/Sobel_operator

### Results are as follows:

<img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/original_image.png" width="250" height="250"><img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/Sobel_kernel.png" width="250" height="250"><img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/Sobel_Fledman_kernel.png" width="250" height="250">

<img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/Scharr_kernel.png" width="250" height="250"><img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/Scharr_kernel.png" width="250" height="250"><img src="https://github.com/sharmasapna/Edge_detection_in_images/blob/master/images/Lapacian_kernel.png" width="250" height="250">

