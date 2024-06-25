# Digital-Image-Processing


Assignment 1
Obtain the images “LenaGray.jpg” and “PeppersGrey.jpg” from the assignment 
directory on MS Teams. Each image has 256 × 256 pixels and each pixel has 8 bits. 
a) Read and display the images. 
b) Define a new 256 × 256 image J as follows: the upper half of J, i.e., the first 
128 rows, should be equal to the upper half of the Lena image. The lower half 
of J, i.e., the 129th row through the 256th row, should be equal to the lower
half of the Peppers image. 
c) Define a new 256 × 256 image K by swapping the upper and lower halves of J.
Turn in: 
1) A listing of your code.
2) Printouts of the original images, image J, and image K.



Assignment 2
Obtain the images “LenaGrayNoisy.jpg” and “PeppersGreyNoisy.jpg” from the 
assignment directory on MS Teams. These are 256 × 256 gray scale images with 8 
bits per pixel. They have been corrupted by salt and pepper noise. 
Write a program to implement (i) Image Negative and (ii) a gray scale Median Filter. 
In the cases of median filter, use a 3 × 3 square structuring element (window). To 
handle edge effects, set output pixels equal to gray level zero when the structuring 
element hangs over the borders of the image. 
(Note: we usually handle edge effects by replication for these filters. But setting the 
output pixels to zero instead simplifies the programming required for doing this 
assignment). 
Turn in: 
1) A listing of your program. 
2) Printouts of the two original images and the results of applying the image 
negative and the median to the original images. 
3) A one page discussion of how the results of the different operators are.
